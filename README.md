// Mengambil form dan elemen-elemen input
const form = document.getElementById('userForm');
const nameInput = document.getElementById('name');
const emailInput = document.getElementById('email');

// Menangani pengiriman form
form.addEventListener('submit', function(event) {
    event.preventDefault(); // Mencegah form untuk mengirimkan data secara default

    // Validasi input
    if (nameInput.value === '' || emailInput.value === '') {
        alert('Semua kolom harus diisi!');
    } else {
        alert('Formulir berhasil dikirim!');
    }
});
