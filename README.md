# DownloadPackageFromNevstopFTP

use [lvcicd](https://github.com/LV-APT/lvCICD/) to download vipm package file from nevstop-lab.

How to Use it:

```
      - name: DownloadPackageFromNevstopFTP
        uses: NEVSTOP-LAB/DownloadPackageFromNevstopFTP@main
        with:
          LabVIEW_Version: 2017
          NEVSTOP-FTP-IP: ${{ secrets.VIPM_FTP_IP }}
          NEVSTOP-FTP-PORT: ${{ secrets.VIPM_FTP_PORT }}
          NEVSTOP-FTP-USER: ${{ secrets.VIPM_FTP_USER }}
          NEVSTOP-FTP-PASSWORDS: ${{ secrets.VIPM_FTP_PASSWORD }}
          PackageName: LabVIEW-GlobalStop-Library
```
