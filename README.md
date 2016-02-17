# Install scripts for **Icinga2** and **Icingaweb2**

## Installing the agent only

Clone it:

    git clone https://github.com/MrAwesomeBro/icinga2-installer.git

Chmod it:

    chmod +x icinga*

Run it:

    ./icinga2_installer

Restart Icinga:

    service icinga2 restart

## Installing the master with Icingaweb2

Clone it:

    git clone https://github.com/MrAwesomeBro/icinga2-installer.git

Chmod them:

    chmod +x icinga*

Run them:

    ./icinga2_installer
    ./icingaweb2_installer

Restart Icinga:

    service icinga2 restart

## Don't forget!

    echo "YourMySQLPassword" > files/mysqlpas.txt
    echo "YourIcingaPassword" > files/icingapass.txt

And after you're done:

    rm -rf files/

# Wiki

The wiki can be found [here](https://github.com/MrAwesomeBro/icinga2-installer/wiki)
