![version](https://img.shields.io/badge/version-20%2B-E23089)
![platform](https://img.shields.io/static/v1?label=platform&message=mac-intel%20|%20mac-arm%20|%20win-64&color=blue)
[![license](https://img.shields.io/github/license/miyako/Cron)](LICENSE)
![downloads](https://img.shields.io/github/downloads/miyako/Cron/total)

# Cron

## Overview

4D Component which includes methods to manage daemons.

## dependencies.json

 ```json
{
	"dependencies": {
		"Cron": {
			"github": "miyako/Cron",
			"version": "latest"
		}
	}
}
```

## Description 

After installation, the following classes become available in the  `cs.Cron` namespace.

- [Cron Class](Cron/Documentation/Classes/Cron.md)
- [Daemon Class](Cron/Documentation/Classes/Daemon.md)

```4d
var $Cron : cs.Cron.Cron
$Cron:=cs.Cron.Cron.new()
```

see [Import Cron](https://github.com/miyako/Cron/blob/main/Cron/Documentation/Methods/Import%20Cron.md) for details.

## Description (legacy)

After installation, one method is added to your 4D project, that can be used to import Cron component's class store.

After you import the class store, you can instantiate Cron and Daemon classes.

```4d
$cs:=Import Cron
$Cron:=$cs.Cron.new()
```

see [Import Cron](https://github.com/miyako/Cron/blob/main/Cron/Documentation/Methods/Import%20Cron.md) for details.

## License

Please refer to ["LICENSE"](LICENSE) file.

## Release Note

Initial release (2021-03-18)

EXECUTE METHOD => Formula (2021-03-21)
