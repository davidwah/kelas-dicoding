# Install NodeJS
Install NodeJS versi 14.x supaya bisa menggunakan eslint dengan lancar. Karena eslint hanya support pada versi 10 lebih.
* `curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -`
* `sudo apt-get install -y nodejs`
* `node --version`
* `npm --version`
```
## `curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -` -> untuk mengambil dan menambahkan pada sistem paket dari Nodesource ke dalam apt repo
## `sudo apt-get install -y nodejs` -> untuk install Node.js 14.x dan npm
## `node --version` -> untuk mengetahui versi nodejs yang terinstal
```

langkah yang pada proyek nodejs-dicoding:
- npm init --y
- npm install nodemon --save-dev
- npm install eslint --save-dev
- npx eslint --init
    ```
    * How would you like to use ESLint? -> To check, find problems, and enforce code style.
    * What type of modules does your project use? -> CommonJS (require/exports).
    * Which framework did you use? -> None of these. 
    * Does your project use TypeScript? -> N.
    * Where does your code run? -> Node (pilih menggunakan spasi).
    * How would you like to define a style for your project? -> Use a popular style guide.
    * Which style guide do you want to follow? -> (Anda bebas memilih, sebagai contoh pilih AirBnB).
    * What format do you want your config file to be in? -> JSON.
    * Would you like to …… (seluruh pertanyaan selanjutnya) -> Y.
    ```
- npm install @hapi/hapi
- menit ke 44
