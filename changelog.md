User Notes
=============================================================================================================

Version x for future – unstable
-------------------------------------------------------------------------------------------------------------
- new - user web settings page
- new - user web setting layout intervensi pilih layout case action plan / vertical card 
- new - tabel jumlah setiap layanan di halaman monitoring
- update - filter untuk memunculkan seluruh kasus
- remove - "Deskripsi Proses", "Deskripsi Hasil" dan "Rencana Tindak Lanjut" di layout versi case action plan

Version 2.1 (update) – 12 Mar 2024
-------------------------------------------------------------------------------------------------------------
- new - tombol filter di halaman kasus
- new - filter memunculkan seluruh kasus
- new - filter basis periode kasus
- new - filter periode kasus
- new - filter basis wilayah
- new - filter wilayah
- new - filter basis pengurangan usia klien
- new - filter kategori klien
- new - filter arsip
- new - tombol filter di halaman detail kasus, tabel intervensi
- new - filter menampilkan agenda intervensi berdasarkan jabatan
- new - filter agenda yang sudah / belum ditindak lanjuti
- new - filter agenda sesuai user yang login
- new - layout tabel intervensi / agenda & kinerja
- new - halaman web settings user
- new - tabel monitoring aktivitas kasus di halaman monitoring
- new - informasi mengenai field apa saja yang dihitung pada Kelengkapan Data
- fix - save formulir terlapor

Version 2.1 (update) – 3 Mar 2024
-------------------------------------------------------------------------------------------------------------
- new - list petugas di modal kasus
- new - floating button Tambah Agenda di halaman laporan kinerja
- new - reaload tabel tetap pada halaman yang sama di halaman laporan kinerja
- new - filter kasus yang diregis di grafik jumlah kasus di halaman monitoring
- fix - gagal tambah agenda karena uuid agenda sebelumnya masih ada
- fix - validasi jika sudah ada no regisnya maka jika approve akan gagal
- update - tombol detail kasus berupa link sehingga dapat dibuka di tab baru
- update - tidak bisa approve kasus ketika sudah kasus diarsipkan
- update - tidak bisa arsipkan kasus ketika sudah ada no regisnya
- remove - tombol hapus kasus ketika sudah ada no regisnya
- remove - centang validasi oleh Sekretariat di halaman laporan kinerja 

Version 2.1 (update) – 18 Feb 2024
-------------------------------------------------------------------------------------------------------------
- new - filter bulan dan tahun di halaman laporan kinerja
- new - filter bulan dan tahun di halaman monitoring laporan kinerja
- new - export laporan kinerja ke PDF sesuai format sekretariat di halaman laporan kinerja
- new - check box validasi agenda untuk sekretariat di halaman laporan kinerja
- new - check box keterangan sudah / belum diTL di halaman laporan kinerja
- new - halaman monitoring laporan kinerja untuk sekretariat
- new - filter tampilkan agenda belum DiTL di halaman laporan kinerja
- remove - hilangkan nama Supervisor Kasus / satpel di list Tgas
- fix - hide formulir tambah/edit agenda as default di form agenda
- fix - menampilkan tombol edit di formulir agenda di dashboard

Version 2.1 – 12 Feb 2024
-------------------------------------------------------------------------------------------------------------
- new - field WYSIWYG "Rencana Tindak Lanjut" di form agenda
- new - field multiple select "Detail Layanan" di form agenda
- new - alert ketika nama user tidak ada di "Tags" di form agenda
- new - uniq array "Tags" untuk mencegah nama petugas terinput 2 kali di form agenda
- new - toggle "Agenda Layanan" & "Agenda Non-Layanan" show/hide & disable/enable field di form agenda
- new - disabled esc & click outer untuk mencegah modal tertutup di form agenda
- new - show detail / view agenda di modal agenda
- new - edit agenda di modal agenda
- update - larger modal width form agenda
- update - label "Keterangan" menjadi "Deskripsi Proses" di form agenda
- update - label "Catatan" menjadi "Deskripsi Hasil" di form agenda
- update - textarea "Deskripsi Proses" menjadi WYSIWYG di form agenda
- update - textarea "Deskripsi Hasil" menjadi WYSIWYG di form agenda
- update - label "Judul Kegiatan" menjadi "Kegiatan" di form agenda
- update - select option "Jenis Agenda" menjadi radio button di form agenda
- update - width "Jam Mulai" menjadi 100% di form agenda
- update - default agenda yang muncul hanya agenda layanan di dashboard
- update - format kolom "Perencanaan Intervensi" di tabel intervensi
- update - format kolom "Pelaksanaan Intervensi" di tabel intervensi
- update - format kolom "Perencanaan Intervensi" di tabel laporan kinerja
- update - format kolom "Pelaksanaan Intervensi" di tabel laporan kinerja
- update - clickable area di tabel intervensi
- remove - menu / link ke halaman dokumen
- remove - field tautkan dokumen di form agenda

Version 2.0 – 01 Jan 2024
-------------------------------------------------------------------------------------------------------------
- Initial Release.


Developer Notes
=============================================================================================================
1 Jan 2024 : 
-------------------------------------------------------------------------------------------------------------
commit 0cfd7e01353e098867e7856c949d19b755b6c0b7 (HEAD -> main)
Author: Addzifi <zivimoch@gmail.com>
Date:   Tue Dec 19 13:27:54 2023 +0700

    initial init

:000000 100644 00000000 1671c9b9 A      .e
ditorconfig
:000000 100644 00000000 832bcbef A      .e
nv
:000000 100644 00000000 f9e1213b A      .e
nv.example
:000000 100644 00000000 30bc1627 A      .g
itingone
:000000 100644 00000000 877ea701 A      .s
tyleci.yml
:000000 100644 00000000 e69de29b A      80
00
:000000 100644 00000000 d8bc1d29 A      ap
p/Console/Kernel.php
:000000 100644 00000000 50a8e0c6 A      ap
p/DataTables/AgendaDataTable.php
:000000 100644 00000000 8e7fbd1b A      ap
p/Exceptions/Handler.php
:000000 100644 00000000 59e85877 A      ap
p/Helpers/LogActivityHelper.php
:000000 100644 00000000 bd5cc616 A      ap
p/Helpers/NotifHelper.php
:000000 100644 00000000 cdaed5cb A      ap
p/Helpers/StatusHelper.php
:000000 100644 00000000 b7be55c9 A      ap
p/Http/Controllers/AgendaController.php
:000000 100644 00000000 ad131868 A      ap
p/Http/Controllers/AsesmenController.php
:000000 100644 00000000 09abe876 A      ap
p/Http/Controllers/Auth/AuthenticatedSessi
onController.php
:000000 100644 00000000 11750100 A      ap
p/Http/Controllers/Auth/ConfirmablePasswor
dController.php
:000000 100644 00000000 3362dcaa A      ap
p/Http/Controllers/Auth/EmailVerificationN
otificationController.php
:000000 100644 00000000 e247f95f A      ap
p/Http/Controllers/Auth/EmailVerificationP
romptController.php
:000000 100644 00000000 1df8e21a A      ap
p/Http/Controllers/Auth/NewPasswordControl
ler.php
:000000 100644 00000000 667ab94b A      ap
p/Http/Controllers/Auth/PasswordResetLinkC
ontroller.php
:000000 100644 00000000 487fedb8 A      ap
p/Http/Controllers/Auth/RegisteredUserCont
roller.php
:000000 100644 00000000 6baa9aa7 A      ap
p/Http/Controllers/Auth/VerifyEmailControl
ler.php
:000000 100644 00000000 b3fe9349 A      ap
p/Http/Controllers/CatatanController.php
:000000 100644 00000000 a0a2a8a3 A      ap
p/Http/Controllers/Controller.php
:000000 100644 00000000 2b0322ae A      ap
p/Http/Controllers/DashboardController.php
:000000 100644 00000000 f3b5d0b6 A      ap
p/Http/Controllers/DokumenController.php
:000000 100644 00000000 cca4efa1 A      ap
p/Http/Controllers/FormPenerimaPengaduan.p
hp
:000000 100644 00000000 0b11bed6 A      ap
p/Http/Controllers/KasusController.php
:000000 100644 00000000 61127b47 A      ap
p/Http/Controllers/LogActivityControler.ph
p
:000000 100644 00000000 d89c066f A      ap
p/Http/Controllers/MonitoringController.ph
p
:000000 100644 00000000 9e8ea852 A      ap
p/Http/Controllers/NotifikasiController.ph
p
:000000 100644 00000000 c3ce1bf8 A      ap
p/Http/Controllers/OpsiController.php
:000000 100644 00000000 f17540e8 A      ap
p/Http/Controllers/PemantauanController.ph
p
:000000 100644 00000000 b30734ed A      ap
p/Http/Controllers/PengumumanController.ph
p
:000000 100644 00000000 4bcfdcc9 A      ap
p/Http/Controllers/PersetujuanController.p
hp
:000000 100644 00000000 d13d7b93 A      ap
p/Http/Controllers/PetugasController.php
:000000 100644 00000000 c23e1ee5 A      ap
p/Http/Controllers/PublicUrlController.php
:000000 100644 00000000 387d7d3c A      ap
p/Http/Controllers/RiwayatKejadianControll
er.php
:000000 100644 00000000 9de479c9 A      ap
p/Http/Controllers/TemplateController.php
:000000 100644 00000000 dbbdcde4 A      ap
p/Http/Controllers/TerminasiController.php
:000000 100644 00000000 78db74cd A      ap
p/Http/Controllers/UsersController.php
:000000 100644 00000000 55399ad2 A      ap
p/Http/Controllers/WilayahController.php
:000000 100644 00000000 d3722c2d A      ap
p/Http/Kernel.php
:000000 100644 00000000 704089a7 A      ap
p/Http/Middleware/Authenticate.php
:000000 100644 00000000 867695bd A      ap
p/Http/Middleware/EncryptCookies.php
:000000 100644 00000000 74cbd9a9 A      ap
p/Http/Middleware/PreventRequestsDuringMai
ntenance.php
:000000 100644 00000000 a2813a06 A      ap
p/Http/Middleware/RedirectIfAuthenticated.
php
:000000 100644 00000000 88cadcaa A      ap
p/Http/Middleware/TrimStrings.php
:000000 100644 00000000 7186414c A      ap
p/Http/Middleware/TrustHosts.php
:000000 100644 00000000 3391630e A      ap
p/Http/Middleware/TrustProxies.php
:000000 100644 00000000 9e865217 A      ap
p/Http/Middleware/VerifyCsrfToken.php
:000000 100644 00000000 940a2d41 A      ap
p/Http/Requests/Auth/LoginRequest.php
:000000 100644 00000000 9894201e A      ap
p/Models/Agenda.php
:000000 100644 00000000 1c4abd20 A      ap
p/Models/Asesmen.php
:000000 100644 00000000 9000a0c6 A      ap
p/Models/Catatan.php
:000000 100644 00000000 1618f879 A      ap
p/Models/DifabelType.php
:000000 100644 00000000 3c5ac2c3 A      ap
p/Models/Dokumen.php
:000000 100644 00000000 bed2fbea A      ap
p/Models/DokumenKeyword.php
:000000 100644 00000000 566ec713 A      ap
p/Models/DokumenTl.php
:000000 100644 00000000 e0fe481b A      ap
p/Models/Kasus.php
:000000 100644 00000000 e968e0f3 A      ap
p/Models/KategoriKasus.php
:000000 100644 00000000 d9ee70bd A      ap
p/Models/Klien.php
:000000 100644 00000000 2be469e7 A      ap
p/Models/KondisiKhusus.php
:000000 100644 00000000 c1d25f43 A      ap
p/Models/LogActivity.php
:000000 100644 00000000 00485242 A      ap
p/Models/MediaPengaduan.php
:000000 100644 00000000 4d8fe584 A      ap
p/Models/Notifikasi.php
:000000 100644 00000000 a698c412 A      ap
p/Models/Pasal.php
:000000 100644 00000000 95539ebd A      ap
p/Models/Pelapor.php
:000000 100644 00000000 0bee606d A      ap
p/Models/Pemantauan.php
:000000 100644 00000000 45bd94c5 A      ap
p/Models/Pengumuman.php
:000000 100644 00000000 69d944df A      ap
p/Models/PersetujuanIsi.php
:000000 100644 00000000 5a18d038 A      ap
p/Models/PersetujuanItem.php
:000000 100644 00000000 ace7b012 A      ap
p/Models/PersetujuanTemplate.php
:000000 100644 00000000 cf82c576 A      ap
p/Models/Petugas.php
:000000 100644 00000000 fa2396e7 A      ap
p/Models/ProgramPemerintah.php
:000000 100644 00000000 1211bb5d A      ap
p/Models/PublicUrl.php
:000000 100644 00000000 fc7821f8 A      ap
p/Models/RiwayatKejadian.php
:000000 100644 00000000 7a8cc6ff A      ap
p/Models/SumberRujukan.php
:000000 100644 00000000 ac7e63d8 A      ap
p/Models/Template.php
:000000 100644 00000000 b8d92196 A      ap
p/Models/TemplateKeyword.php
:000000 100644 00000000 ccfb6166 A      ap
p/Models/Terlapor.php
:000000 100644 00000000 5f82978d A      ap
p/Models/Terminasi.php
:000000 100644 00000000 c6a5f5ee A      ap
p/Models/TindakKekerasan.php
:000000 100644 00000000 53c9db9f A      ap
p/Models/TindakLanjut.php
:000000 100644 00000000 c6d94477 A      ap
p/Models/User.php
:000000 100644 00000000 ee8ca5bc A      ap
p/Providers/AppServiceProvider.php
:000000 100644 00000000 22b77e6e A      ap
p/Providers/AuthServiceProvider.php
:000000 100644 00000000 395c518b A      ap
p/Providers/BroadcastServiceProvider.php
:000000 100644 00000000 23499eb8 A      ap
p/Providers/EventServiceProvider.php
:000000 100644 00000000 ca027ea3 A      ap
p/Providers/RouteServiceProvider.php
:000000 100644 00000000 21376836 A      ap
p/Traits/Uuid.php
:000000 100644 00000000 b45d3425 A      ap
p/View/Components/AppLayout.php
:000000 100644 00000000 04cc559e A      ap
p/View/Components/GuestLayout.php
:000000 100755 00000000 67a3329b A      ar
tisan
:000000 100644 00000000 037e17df A      bo
otstrap/app.php
:000000 100644 00000000 d6b7ef32 A      bo
otstrap/cache/.gitignore
:000000 100644 00000000 318f3c7c A      co
mposer.json
:000000 100644 00000000 0abe9432 A      co
mposer.lock
:000000 100644 00000000 d1f3f7e0 A      co
nfig/app.php
:000000 100644 00000000 d8c6cee7 A      co
nfig/auth.php
:000000 100644 00000000 2d529820 A      co
nfig/broadcasting.php
:000000 100644 00000000 8736c7a7 A      co
nfig/cache.php
:000000 100644 00000000 8a39e6da A      co
nfig/cors.php
:000000 100644 00000000 b42d9b30 A      co
nfig/database.php
:000000 100644 00000000 54bd7871 A      co
nfig/datatables-buttons.php
:000000 100644 00000000 760ef972 A      co
nfig/filesystems.php
:000000 100644 00000000 bcd3be4c A      co
nfig/hashing.php
:000000 100644 00000000 880cd922 A      co
nfig/logging.php
:000000 100644 00000000 f96c6c7c A      co
nfig/mail.php
:000000 100644 00000000 25ea5a81 A      co
nfig/queue.php
:000000 100644 00000000 9281c92d A      co
nfig/sanctum.php
:000000 100644 00000000 2a1d616c A      co
nfig/services.php
:000000 100644 00000000 ac0802b1 A      co
nfig/session.php
:000000 100644 00000000 22b8a18d A      co
nfig/view.php
:000000 100644 00000000 7eec8b68 A      da
tabase/factories/AsesmenFactory.php
:000000 100644 00000000 4b1c4f61 A      da
tabase/factories/CatatanFactory.php
:000000 100644 00000000 9da42620 A      da
tabase/factories/DifabelTypeFactory.php
:000000 100644 00000000 a9bc68ff A      da
tabase/factories/JadwalFactory.php
:000000 100644 00000000 554c8ee5 A      da
tabase/factories/KasusFactory.php
:000000 100644 00000000 5d2049ef A      da
tabase/factories/KategoriKasusFactory.php
:000000 100644 00000000 f5ab67c8 A      da
tabase/factories/KlienFactory.php
:000000 100644 00000000 4f86b9aa A      da
tabase/factories/KondisiKhususFactory.php
:000000 100644 00000000 c2812260 A      da
tabase/factories/LayananFactory.php
:000000 100644 00000000 efb6f2b6 A      da
tabase/factories/MonitoringFactory.php
:000000 100644 00000000 f6e62b8f A      da
tabase/factories/PasalFactory.php
:000000 100644 00000000 c89e69e6 A      da
tabase/factories/PelaporFactory.php
:000000 100644 00000000 998fbd49 A      da
tabase/factories/PengumumanFactory.php
:000000 100644 00000000 04636fb6 A      da
tabase/factories/PetugasFactory.php
:000000 100644 00000000 3c4c882f A      da
tabase/factories/ProgramPemerintahFactory.
php
:000000 100644 00000000 7a6bce44 A      da
tabase/factories/PublicUrlFactory.php
:000000 100644 00000000 c4b3d0c3 A      da
tabase/factories/RiwayatFactory.php
:000000 100644 00000000 e1bc260c A      da
tabase/factories/TemplateFactory.php
:000000 100644 00000000 34fc1250 A      da
tabase/factories/TerlaporFactory.php
:000000 100644 00000000 cf8023bf A      da
tabase/factories/TerminasiFactory.php
:000000 100644 00000000 62e9a638 A      da
tabase/factories/TindakKekerasanFactory.ph
p
:000000 100644 00000000 74773aa1 A      da
tabase/factories/TindakLanjutFactory.php
:000000 100644 00000000 c939442c A      da
tabase/factories/UserFactory.php
:000000 100644 00000000 3b795184 A      da
tabase/migrations/2014_10_12_000000_create
_users_table.php
:000000 100644 00000000 0ee0a36a A      da
tabase/migrations/2014_10_12_100000_create
_password_resets_table.php
:000000 100644 00000000 2379b086 A      da
tabase/migrations/2016_08_03_072729_create
_provinces_table.php
:000000 100644 00000000 6a917a5d A      da
tabase/migrations/2016_08_03_072750_create
_cities_table.php
:000000 100644 00000000 f5b466ed A      da
tabase/migrations/2016_08_03_072804_create
_districts_table.php
:000000 100644 00000000 9501bca9 A      da
tabase/migrations/2016_08_03_072819_create
_villages_table.php
:000000 100644 00000000 6aa6d743 A      da
tabase/migrations/2019_08_19_000000_create
_failed_jobs_table.php
:000000 100644 00000000 4315e16a A      da
tabase/migrations/2019_12_14_000001_create
_personal_access_tokens_table.php
:000000 100644 00000000 75b63e88 A      da
tabase/migrations/2023_03_08_061319_create
_agendas_table.php
:000000 100644 00000000 96c0b3df A      da
tabase/migrations/2023_03_08_062602_create
_tindak_lanjuts_table.php
:000000 100644 00000000 6168532e A      da
tabase/migrations/2023_03_14_085602_create
_dokumen_tls_table.php
:000000 100644 00000000 77145d34 A      da
tabase/migrations/2023_05_17_082054_create
_pelapors_table.php
:000000 100644 00000000 d493c94a A      da
tabase/migrations/2023_05_17_085626_create
_kasuses_table.php
:000000 100644 00000000 883738c3 A      da
tabase/migrations/2023_05_17_092903_create
_terlapors_table.php
:000000 100644 00000000 bc651b71 A      da
tabase/migrations/2023_05_23_044517_create
_kliens_table.php
:000000 100644 00000000 6eab38a3 A      da
tabase/migrations/2023_05_24_021623_create
_kategori_kasuses_table.php
:000000 100644 00000000 a0a161d4 A      da
tabase/migrations/2023_05_24_021641_create
_tindak_kekerasans_table.php
:000000 100644 00000000 571a8c91 A      da
tabase/migrations/2023_05_24_021704_create
_difabel_types_table.php
:000000 100644 00000000 637a27c3 A      da
tabase/migrations/2023_05_24_021719_create
_program_pemerintahs_table.php
:000000 100644 00000000 a165c59a A      da
tabase/migrations/2023_05_24_094615_create
_kondisi_khususes_table.php
:000000 100644 00000000 701fa750 A      da
tabase/migrations/2023_05_29_031046_create
_pasals_table.php
:000000 100644 00000000 422934af A      da
tabase/migrations/2023_06_03_162943_create
_petugas_table.php
:000000 100644 00000000 7c23df2c A      da
tabase/migrations/2023_07_06_083911_create
_riwayat_kejadians_table.php
:000000 100644 00000000 bb08a7d1 A      da
tabase/migrations/2023_07_11_023252_create
_templates_table.php
:000000 100644 00000000 549c909d A      da
tabase/migrations/2023_07_12_042621_create
_template_keywords_table.php
:000000 100644 00000000 c4fd3794 A      da
tabase/migrations/2023_07_12_083003_create
_dokumens_table.php
:000000 100644 00000000 1029e62a A      da
tabase/migrations/2023_07_12_085829_create
_dokumen_keywords_table.php
:000000 100644 00000000 d3734762 A      da
tabase/migrations/2023_07_23_051134_create
_persetujuan_isis_table.php
:000000 100644 00000000 92dc0f2a A      da
tabase/migrations/2023_07_23_072840_create
_persetujuan_templates_table.php
:000000 100644 00000000 518d8092 A      da
tabase/migrations/2023_07_23_092625_create
_persetujuan_items_table.php
:000000 100644 00000000 a83d44c8 A      da
tabase/migrations/2023_08_30_035241_create
_log_activities_table.php
:000000 100644 00000000 907a4454 A      da
tabase/migrations/2023_08_30_072342_create
_notifikasis_table.php
:000000 100644 00000000 609aa39d A      da
tabase/migrations/2023_09_05_102133_create
_asesmens_table.php
:000000 100644 00000000 e38a0b61 A      da
tabase/migrations/2023_09_17_170046_create
_pemantauans_table.php
:000000 100644 00000000 86957928 A      da
tabase/migrations/2023_09_18_140114_create
_terminasis_table.php
:000000 100644 00000000 6ada45c2 A      da
tabase/migrations/2023_09_24_094613_create
_catatans_table.php
