## How to create a pre-built binary?
Execute the following commands:
```
brew install --build-bottle <formula>
brew bottle <formula>
```
`<formula>` is the name of your project. For example: contentgen or translationgen.
Upload the binary to this repository and update the hash value in the brew formula file.
