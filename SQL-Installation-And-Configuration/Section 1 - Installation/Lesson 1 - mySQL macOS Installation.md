# Installing MySQL Server on macOS
Before installing MySQL server on macOS, let's make sure that we don't already have MySQL server installed on our device!

To check if MySQL is installed or not, follow the following steps:
1. Go to `System Settings`,
2. In the Search bar on the top-left, type `MySQL`
![img.png](../../Resources/img.png)
3. If you get the following on typing `MySQL`, then you already have `MySQL` server installed on your machine.
![img.png](../../Resources/img2.png)
4. Otherwise, you don't have `MySQL` server installed on your machine, and you proceed with the following steps!
5. Go to [this](dev.mysql.com), click on `MySQL Community Server` and 
   1. If you are using Windows, follow the following steps:
      1. The webpage will automatically detect 
   2.  If you are using macOS, follow the following steps:
        1. The webpage, will automatically detect the version of your OS, your job is to select and download the software package that is developed for your device's processor architecture, if you are using a macOS with an `M-Series` SoC CPU, download the software package built for `ARM, 64-bit`, otherwise, download the one built for `x86, 64-bit`.
       2. In the next page, you'll get the option to create an Oracle account, but you can skip that step and simply proceed with the download. 
       3. Once downloaded, click on the `.dmg` file and start the installation procedure. 
       4. While installing the MySQL Server, you'll get an option to select between `Use Strong Password Encryption` and `Use legacy Password Encryption`, select the latter if you want compatibility with older versions of MySQL Connectors or clients and the former if you want Strong password encryption.
       5. Next, you'll get an option to enter the password for the `root` user, keep in mind to note the password you enter here because without it, you'll not be able to use this MySQL server installation then press Next, and we are done!
       6. Go to `System Settings` and search for `MySQL` in the search bar to check if MySQL was successfully installed or not. If so, you'll find a listing named 'MySQL' and nothing otherwise.
   3. If you are using Linux, follow the following steps:
