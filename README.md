# cv_masters_lockers
Distributed system project

1. [Basic architecture](#architecture)
2. [Post/Get requests](#requests)

## Basic architecture <a name="architecture"></a>
![](https://github.com/AdoreIt/cv_masters_lockers/blob/master/architecture_diagram.png?raw=true)

## Requests format <a name="requests"></a>

### Get:
```
_Check_="name"   // request of _Check_ button
_Clear_="name"	 // request of _Clear_ button
```

### Post:
```
_LockerBusy_="name"     //All lockers are busy
_GetKey_="name":"key"   //User got key
_Return_="name":"key"   //User returned key
_Success_               //_Clear_ action was successfull
```
