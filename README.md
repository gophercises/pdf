# Exercise #20: Building PDFs

[![exercise status: in progress](https://img.shields.io/badge/exercise%20status-in%20progress-yellow.svg?style=for-the-badge)](https://gophercises.com/exercises/pdf)

## Exercise details

There are two goals with this exercise.

1. Create a PDF invoice given some data about a fake customer's recent transactions
2. Generate a course completion certificate for Gophercises and add your name to it!

*Whoa, what?!?* Yep, you read that right. Many courses will give you a course completion certification. This one teaches you to generate it yourself! Sweet, right? 😎

### Creating a PDF invoice

Given data like the following, generate a PDF invoice:

```go
data := []struct {
		UnitName       string
		PricePerUnit   int
		UnitsPurchased int
	}{
		{
			UnitName:       "2x6 Lumber - 8'",
			PricePerUnit:   375, // in cents
			UnitsPurchased: 220,
		}, {
			UnitName:       "Drywall Sheet",
			PricePerUnit:   822, // in cents
			UnitsPurchased: 50,
		}, {
			UnitName:       "Paint",
			PricePerUnit:   1455, // in cents
			UnitsPurchased: 3,
		},
	}
```

The invoice should look something like this:

### Course Completion Certificat

Create a course completion cert.

TODO(joncalhoun): Finish this section.
