## script cod - copy

```ts
  function cop() {
        const text = "your text";
        //const sco = document.querySelector('.copt');
        navigator.clipboard.writeText(text)
          .then(() =>
            sco.innerText = "copied!")
          //alert("Copied: " + text))
          .catch(err => console.error("Error when copying", err));
}
```
