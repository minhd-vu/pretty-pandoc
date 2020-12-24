# pretty-pandoc

Generate beautiful pdfs from github markdown files using pandoc.

## Usage
```sh
./pandoc-script.sh [file_name].md [file_name].pdf
```

## Dependencies

* MacOS
    ```sh
    brew install mactex librsvg
    ```

* Ubuntu/Debian
    ```sh
    sudo apt install texlive-xetex librsvg2-bin texlive-science
    ```

Source: [https://learnbyexample.github.io/customizing-pandoc/](https://learnbyexample.github.io/customizing-pandoc/)
