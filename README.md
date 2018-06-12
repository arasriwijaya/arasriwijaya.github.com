# INTRODUCE

CV. ARA Sriwijaya didirikan oleh Bapak R.Ainul Yakin,ST yang berdarah Palembang. Sejak lulus SMA sampai lulus kuliah jurusan Teknik Arsitektur, beliau sudah belajar, berkarya dan bekerja di bidang Marketing produk barang, organizer, konsultan bangunan dan kontraktor sipil, hasil karya desain nya pun sudah terlihat di sebagian besar kota Palembang. Dengan tekad, gigih dan keinginan yang kuat untuk mandiri membuat dirinya mendirikan perusahaan berawal dari Studio Creative Design sampai perseroan komonditer CV.ARA Sriwijaya saat ini berjalan.

CV. ARA Sriwijaya Sebagai perusahaan yang bergerak dibidang Pengadaan barang dan jasa yang di dirikan pada tahun 2018, kami menyediakan solusi bisnis yang inovatif kepada perusahaan yang menjadi mitra kami, melayani perusahaan menengah dan perusahaan besar, baik Swasta, BUMN dan Pemerintahan.

CV. ARA Sriwijaya dalam menjalankan binisnya mempunyai Team/ Crew yang telah berpengalaman,dan berkompeten agar tercipta kualitas yang terbaik, yang mana kami selalu mengutamakan mutu serta kepercayaan demi kelangsungan bisnis yang harmonis dan berkelanjutan.

Tujuan kami adalah sebagai perusahaan Jasa konsultan, Jasa konstruksi, Organizer, Perdagangan dan Pengadaan barang yang terbaik dan terpercaya serta selalu menjadi pilihan konsumen melalui keunggulan kami dalam kualitas produk dan pelayanan terbaik konsumen.

# Pre-Requisites

Installation recon-ng from Source

1. Clone the Recon-ng repository

    `git clone https://LaNMaSteR53@bitbucket.org/LaNMaSteR53/recon-ng.git`
2. Change into the Recon-ng directory.

    `cd recon-ng`

3. Install dependencies.

    `pip install -r REQUIREMENTS`

4. Eventually link the installation directory to /usr/share/recon-ng

    `ln -s /$recon-ng_path /usr/share/recon-ng`

5. Optionally (highly recommended) download: 

    + Alt-DNS (https://github.com/infosec-au/altdns)
    + and a good subdomain bruteforce list (https://github.com/danielmiessler/SecLists/blob/master/Discovery/DNS/sorted_knock_dnsrecon_fierce_recon-ng.txt)

6. Create config.py file and specify the path to recon-ng and allDNS as it showed in config_sample.py

# Basic Usage

`./enumall.py domain.com`

also supports:
+ -w to run a custom wordlist with recon-ng
+ -a to use alt-dns
+ -p to feed a custom permutations list to alt-dns (requires -a flag)
+ -i to feed a list of domains (can also type extra domains into the original command)

# Advanced Usage

`./enumall.py domain1.com domain2.com domain3.com -i domainlist.txt -a -p permutationslist.txt -w wordlist.com`

Output from recon-ng will be in `.lst` and `.csv` files, output from alt-dns will be in a `.txt` file


by @jhaddix and @leifdreizler
