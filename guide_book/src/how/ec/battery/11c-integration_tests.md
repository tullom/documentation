# Integration testing

We've created _unit tests_ for our Mock Battery, but we haven't tested it _in situ_ for its behaviors yet.

Although we do have console output and a `main()` function available we can run to see some of this, we haven't created a similar test for this.

We will revisit testing -- and specifically integration testing -- after we have completed the exercise for the 
`Charger` component.  Once that is available, we'll be able to test a combined integration that validates the behavior of our battery as it is discharged and charged through different cycles.