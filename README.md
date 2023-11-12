# Quality Assurance Assignment

Please read each note very carefully!

The application is a simple CRUD tooling that has below domain object
```
Customer {
	Firstname
	Lastname
	DateOfBirth
	PhoneNumber
	Email
	BankAccountNumber
}
```
### Assignment

Create a test scenario in Gherkins format that follows the business rules and is used by QA engineer for manual testing.
keep in mind the same script will be used to create automated E2E testing.

### Validations (Must)

- During Create; validate the phone number to be a valid *mobile* number only.

- A Valid email and a valid bank account number must be checked before submitting the form.

- Customers must be unique in database: By `Firstname`, `Lastname` and `DateOfBirth`.

- Email must be unique in the database.

### Delivery (Must)
- Please clone this repository in a new github repository in private mode and share with ID: `mason-chase` in private mode on github.com, make sure you do not erase my commits and then create a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) (code review).

