reddit uses Crowdin for translations.

See the getting started guide for more information:
	http://www.reddit.com/r/i18n/wiki/getting_started
	
## Updating reddit translations

    $ cd src/i18n
    $ git pull
    $ make clean
    $ make all
    $ sudo reddit-restart
