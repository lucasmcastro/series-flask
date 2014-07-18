### Como Instalar

1. Instale o Mongo

    No Linux

    ```sh
    $ apt-get update
    $ apt-get install mongodb
    ```

    No Mac OSX (com brew)

    ```sh
    $ brew update
    $ brew install mongodb
    ```

2. Baixe o projeto
    ```sh
    $ git clone http://git@github.com/lucasmcastro/series-flask
    $ cd series-flask
    $ pip install -r requirements.txt
    ```

3. Rode o mongo em uma shell
    ```sh
    $ mongod
    ```

4. Rode a aplicação em outra shell
    ```sh
    $ python app.py
    ```
5. Acesse a aplicação no browser através de http://127.0.0.1:5000
