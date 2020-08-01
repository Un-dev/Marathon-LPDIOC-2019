#MARATHON 2019 - 2020**

___

## Installation

### copy a new .env.local => cp .env .env.local


**Change in env.local** *db_user, db_password, db_name by your configuration*


```
DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name?serverVersion=5.7
```

##### then

```
./install
```
___

## Launch Server Symfony local
```
./symfony server:start -d
```

## kill Server Symfony local
```
./symfony server:stop
```
___

## Update CSS or/and JS

### Avec yarn

##### Dev

```
yarn run encore dev
```

##### Prod

```
yarn run encore production
```

### Avec npm

##### Dev
```
npm run dev
```

##### Prod

```
npm run build
```
___

## Utilisateur

| Username   |      Password      |  Role |
|:----------|:-------------|:------|
| ZimZim |  ZimZim | ROLE_ADMIN |
| Fred |   Fred   |   ROLE_ADMIN |
| Gilles |   Gilles   |   ROLE_USER |
| Sebastien |   Sebastien   |   ROLE_USER |

___


## For upload File ( SysAdmin Only )
```
chown -R www-data:www-data public/images/users
chown -R www-data:www-data public/video/series
```

___



## Enjoy and team play



Coréalisé par François Lannoy, Mathieu Degand, Christophe Guide, Romain Peliks, Said Ladghem.
