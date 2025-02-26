# my-blog
Follow the steps and fastly deploy the source code to github page.

- Install Git and NodeJS (with npm)
  ```
  # Verify installation
  git --version
  node -v
  npm -v
  ```

To install NodejS on Windows without administration authority, try ti use fnm:

```
# Download and install fnm:
winget install Schniz.fnm

# Download and install Node.js:
fnm install 22

# Verify the Node.js version:
node -v # Should print "v22.14.0".

# Verify npm version:
npm -v # Should print "10.9.2".

```

And I have find that NodeJS v22 reported some of the installation issues, refer here: https://github.com/nodejs/node/issues/21829  

To avoid it, just use v21 instead.  

The environment variables should be added mannually when use fnm to install:

```
$env:PATH += "C:\Users\<USERNAME>\AppData\Roaming\fnm\node-versions\v21.0.0\installation"
```