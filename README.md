# rn-auto-id
Automated Test ID's addition to react native.

### Setup & Run

1.  `npm install -g jscodeshift`
1.  `git clone https://github.com/ohheyitskartik/rn-auto-id` or download a zip file from `https://github.com/ohheyitskartik/rn-auto-id/archive/main.zip`
1.  `jscodeshift -t <codemod-script> <path>`
    * `codemod-script` - path to the transform file, see available scripts below;
    * `path` - files or directory to transform;
    * use the `-d` option for a dry-run and use `-p` to print the output for comparison;
    * use the `--extensions` option if your files have different extensions than `.js` (for example, `--extensions js,jsx`);
    * if you use flowtype, you might also need to use `--parser=flow`;
    * see all available [jscodeshift options](https://github.com/facebook/jscodeshift#usage-cli).
