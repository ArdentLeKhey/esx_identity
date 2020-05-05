# esx_identity
#### *Reskin of esx_identity*

This is my reskin of esx_identity, you can find original file here : [original esx_identity](https://github.com/ESX-Org/esx_identity) 

Here a video presentation :
[![Video](https://github.com/ArdentLeKey/esx_identity/blob/master/esx_identity.PNG)](https://www.youtube.com/watch?v=jtcZ4IQOF0Q)

## Requirements
* Dependencies For Full Functionality
  * [esx_skin](https://github.com/ESX-Org/esx_skin)
  * [esx_policejob](https://github.com/ESX-Org/esx_policejob)
  * [esx_society](https://github.com/ESX-Org/esx_society)
  
## Installation
- Import `esx_identity.sql` in your database
- Add this to your `server.cfg`:

```
start esx_identity
```

- If you are using esx_policejob or esx_society, you need to enable the following in the scripts' `config.lua`:
```Config.EnableESXIdentity          = true```

### Commands
```
/register
/charlist
/charselect
/chardel
```

## Support

You can ask for help on these discords:

[My discord](https://discord.gg/hEhcEE4)

[Mutual aid discord](https://discord.gg/EzwYgdV)

## License
[MIT](https://choosealicense.com/licenses/mit/)
