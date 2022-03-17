# About the RentX
Rentx is an Rental Car backend platform. 

## Business Rules
The most important requirements and Business Rules. Separated by
- (FR) Functional Requirement
- (NFR) Non Functional Requirement
- (BR) Business Rule

### Cars

#### Register Car
**Functional Requirement**
- [X] Should be able to register an new Car

**Business Rule**
- [X] Should be registered only by ```admins``` users.
- [X] Should be registered with the ```available``` default ```true```.
- [X] Should not be able to register an car with an existing ```license_plate```.

#### List Cars

**Functional Requirement**
- [X] Should be able to list all available cars.
- [X] Should be able to list all available by category name.
- [X] Should be able to list all available by brand.
- [X] Should be able to list all available by car name.

**Business Rule**
- [X] Any user should be able to list available cars.

#### Update Cars

**Functional Requirement**
- [ ] Should be able to update an existing car.

**Business Rule**
- [ ] Should not be able to update an nonexistent car.
- [ ] Should not be able to update an ```license_plate``` with an that already exists.

### Specifications

#### Create Specification

**Functional Requirement**
- [ ] Should be able to register an new specification.

**Business Rule**
- [ ] Should be registered only by ```admins``` users.

#### Car Specification Register
**Functional Requirement**
- [X] Should be able to register an new specification to an car.

**Business Rule**
- [X] Should not be able to register an specification for an non existing car.
- [X] Should not be able to register an already existing specification for same car.
- [X] Should be registered only by ```admins``` users.

#### List Specifications

**Functional Requirement**
- [ ] Should be able to list all available specifications.
- [ ] Should be able to list all cars.

### Categories

#### Create Category
**Functional Requirement**
**Business Rule**

#### List Categories
**Functional Requirement**
**Business Rule**

#### Import Categories
**Functional Requirement**
**Business Rule**








### Users

#### Authenticate User
**Functional Requirement**
**Business Rule**

#### Create User
**Functional Requirement**
**Business Rule**

#### Update User Avatar
**Functional Requirement**
**Business Rule**



### Rental

#### Create Rental

**Functional Requirement**
- [ ] Should be able to create an rental.

**Business Rule**
- [ ] The rental ```expect_return_date``` parameter should be at least 24 hours by default.
- [ ] Should not be possible register an new rental, if an old rental already exists for current account. 