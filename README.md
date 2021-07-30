# jsonbible.github.io
Bible in JSON format

## Usage showcase

1. Print out John 1:1 from Greek Textus Receptus:
  ```bash
  curl -s jsonbible.github.io/tr.json | fx .books[4-1].chapters[1-1].verses[1-1] "`«`+this.text+`» (`+this.name+`)`"
  ```
