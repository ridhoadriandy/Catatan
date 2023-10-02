# Catatan
Berisi Catatan perintah penting untuk React js dan Next js / Javascript, Typescript, JS ES6

// SETUP
1. folder (site) merupakan folder utama yang akan dijalankan
2. "npm install react-icons react-hook-from clsx" menginstall package react icon, memudahkan validasi dan css dinamis
3. "npm install bcrypt mongodb mongoose next-auth" menginstall package backend mongodb dan next auth

// REACT
1. useState = untuk menginisialisasi variabel berulang kali / recycle
2. useRef/forwardRef = untuk melakukan proses / aksi tanpa harus merender tampilan atau component, bisa juga sebagai manipulasi DOM seperti getElementbyId
3. useEffect = melakukan aksi/proses setelah semua tampilan atau component sudah dirender, ada 4 macam useEffect.

// JAVASCRIPT
1. myArray.push('JavaScript'); untuk memasukan data kedalam array dibarisan terakhir
2. myArray.shift(); myArray.unshift("Apple"); untuk menghapus baris pertama array terus memasukan kembali data baru diawal
3. myArray.splice(2, 2);   // Menghapus dari index 2 sebanyak 2 elemen kebelakang
4. month.splice(1, 0, 'February'); // menambahkan element baru setelah index 1 berisi february
5. function sum(...numbers) {}; artinya menambah semua data didalam parameter numbers, sebagai contoh console.log(sum(1, 2, 3, 4, 5));

// ES6 JS
1. const allFavorites = [...favorites, ...others]; const newObj = { ...obj1, ...obj2 }; menggabungkan 2 data menjadi 1, bisa bersifat array maupun object
2. const { firstName, lastName, age } = profile; membuatkan semua isi dari object menjadi variable tanpa perlu memanggil profile.firstName
3. const { firstName: localFirstName, lastName: localLastName, age: localAge } = profile; contoh sintak lain inisialisasi variabel pada object
4. console.log(capital.get("New Delhi")); pada mapping memiliki key dan value, fungsi get untuk mengambil value berdasarkan key
5. const numberSet = new Set([1, 4, 6, 4, 1]); artinya memasukan data agar tidak ada duplikasi, dan data ditampilkan secara berurutan langsung

// INISIALISASI
1. type Variant = 'LOGIN' | 'REGISTER'; artinya terdapat 2 data yang dapat digunakan dalam 1 variabel, bisa digunakan pada parameter
--> const [variant, setVariant] = useState<Variant>('LOGIN');

2. 
