# Airbnb API

REST & GraphQL API of the Airbnb Clone using Django REST Framework and Graphene GraphQL

### API Actions

- [ ] List Rooms
- [ ] Filter Rooms
- [ ] Search By Coords
- [ ] Login
- [ ] Create Account
- [ ] See Room
- [ ] Add Room to Favourites
- [ ] See Favs
- [ ] See Profile
- [ ] Edit Profile

### Create Dev Env:

```shell
$ pipenv instal
```
### Migrations:

```shell
$ python manage.py makemigrations
$ python manage.py migrate --run-syncdb
```


### Create the SuperUser:

```shell
$ python manage.py createsuperuser
```
### Create Fake Data(Seed the DB):
```shell
$ python manage.py mega_seed
```