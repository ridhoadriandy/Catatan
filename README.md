# Catatan
Berisi Catatan perintah penting untuk React js dan Next js / Typescript

// SETUP
1. folder (site) merupakan folder utama yang akan dijalankan
2. "npm install react-icons react-hook-from clsx" menginstall package react icon, memudahkan validasi dan css dinamis
3. "npm install bcrypt mongodb mongoose next-auth" menginstall package backend mongodb dan next auth

// REACT
1. useState = untuk menginisialisasi variabel berulang kali / recycle
2. useRef/forwardRef = untuk melakukan proses / aksi tanpa harus merender tampilan atau component, bisa juga sebagai manipulasi DOM seperti getElementbyId
3. useEffect = melakukan aksi/proses setelah semua tampilan atau component sudah dirender, ada 4 macam useEffect.

// INISIALISASI
1. type Variant = 'LOGIN' | 'REGISTER'; artinya terdapat 2 data yang dapat digunakan dalam 1 variabel, bisa digunakan pada parameter
--> const [variant, setVariant] = useState<Variant>('LOGIN');

2. 
