# mppl

sequenceDiagram
  participant User
  participant System

  User->>System: Membuka halaman register
  System->>User: Menampilkan form register
  User->>System: Mengisi data diri
  System->>User: Memvalidasi data diri
  User->>System: Mengkonfirmasi data diri
  System->>User: Menyimpan data diri
  System->>User: Mengirim email aktivasi
  User->>System: Mengklik link aktivasi
  System->>User: Mengaktifkan akun
  User->>System: Login
