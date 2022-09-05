# Tanya dan Jawab

## Apa yang dimaksud dengan GOPATH dan GOROOT dan ini harus kita set?
`GOPATH` adalah folder yang ditunjuk oleh golang library sebagai tempat kerja atau kita sering sebut dengan `workspace`
`GOROOT` adalah pointer/path folder yang menunjukkan binary dari golang biasanya jika install default kita akan mengarah ke folder `/usr/local/bin`
Harus diset terlebih dahulu, tetapi jika kamu melakukan instalasi menggunakan package biasanya set ini tidak perlu karena sudah dibantu oleh installer untuk melakuakn setting-nya.

## Bagaimana cara melakukan setting manual GOPATH dan GOROOT
Jika ingin melakukan setting manual environment maka perlu lakukan ini
* buka file `.bashrc` atau `.bash_profile`
* lalu pakai editor untuk melakukan edit, bisa pakai `vi`, `vim` atau `nano`
* tambahkan perintah ini di bagian paling bawah
  ```bash
  # for golang programming
  export GOROOT="/usr/local/go"
  export GOPATH="$HOME/Documents/go"
  export PATH="$HOME/Documents/go/bin:$PATH"
  ```

## Jadi apa sih nanti programmer backend itu?
Bisa dilihat nih untuk backend programmer itu akan bagaimana prospect ke depannya. Bisa dilihat disini https://github.com/kamranahmedse/developer-roadmap. Khusus untuk golang developer bisa dilihat [disini](https://roadmap.sh/golang)