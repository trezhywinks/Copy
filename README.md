## script cod - copy

```ts
    <button class="shared" onclick="cop();" id="link-2">copied</button>
```


```ts
  function cop() {
        const text = "your text";
        const sco = document.querySelector('.shared');
        navigator.clipboard.writeText(text)
          .then(() =>
            sco.innerText = "copied!")
          //alert("Copied: " + text))
          .catch(err => console.error("Error when copying", err));
}
```
