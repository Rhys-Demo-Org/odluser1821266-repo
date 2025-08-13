# Readme
This is used in the 'Verify WizCLI Scans and Confirm Production Deployment' lab.

You will need gulp installed to build this

Once build run:

```bash
npm install -g gulp
```

Then to test built version:
```bash
gulp
node dist/app.js
```

View in browser:
```bash
http://localhost:3000
```

And to test built version in a container locally

```bash
gulp docker
```

View in browser:
```bash
http://localhost:3000
```
