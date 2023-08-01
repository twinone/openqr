# Embeddable QR code

If you want to display a QR code in your browser without a build system, it's sometimes convenient to use an iframe.
It's kinda overkill to set up a backend, and untrustworthy to use any "free APIs" around.

Github Pages to the rescue

Based on: [QRCode.js](https://github.com/davidshimjs/qrcodejs)

### Examples:

https://twinone.github.io/openqr?width=1024&height=1024&fg=red&bg=black&text=https://google.com/
https://twinone.github.io/openqr?text=https://github.com/twinone/openqr


# Usage
```

<iframe src="https://twinone.github.io/openqr?<params>"></iframe>


```

Params for reference:
```
const text = getParameterByName("text") || "https://www.google.com";
const width = getParameterByName("width") || 256;
const height = getParameterByName("height") || 256;
const fg = getParameterByName("fg") || "#000000";
const bg = getParameterByName("bg") || "#ffffff";
```



