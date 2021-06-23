# fruitShopDjangoTest

### Synopsis:

Fruit shop needs a platform to manage their products and sells.
This platform should contain a place to manage products another one for sells and should require a login to use it.

Requirements:

django admin resources are not allowed
virtualenv
python3.6
django1.11 or django2
Pages (as templates):

-- login
-- CRUD for products
-- CRUD for sells
-- must exist a logout button somewhere


all views should be documented (docstrings even if autogenerated)
at least three apps (products, sells, users)
mandatory to use javascript or jquery
all CRUDs should be handled through an API (can be in the apps or have a app just for that) [if possible do not use Django Rest Framework]

all create and update and delete calls should be executed through javascript (ajax ...) [not mandatory but a plus]

unit/functional tests for each app (can be something simple like call an API and check response status) [not mandatory but a plus]

the project should have a normal folder structure (docs, src, tests, requirments.txt)
documentation is mandatory (even if short) and should at least contain information on how to run project and tests
it can be delivered via git


### To do:
- [x] template bootstrap
- [x] tests user creation
- [x] tests user login

- [x] admin add products
- [x] admin list products
- [x] admin edit products
- [x] template menu admin
- [x] admin permissions

- [x] customer list products
- [x] customer add to cart products
- [ ] template menu customer
- [ ] customer permissions

- [x] temporary rest framework
- [x] jquery rest client
- [x] remove temporary rest framework

- [x] custom rest product list view + serializer
- [x] custom rest product add view
- [x] add to shopping cart using rest
- [ ] delele cart item using rest
- [ ] replace generic views with simple views