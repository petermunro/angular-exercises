
# Angular Testing

1. Write a test for the `PlayService` service which tests that an initial call to `.getPlays()` returns the correct number of entries, and checks one or two of the play values.

2. Write a test to verify that `.addPlay()` adds a correctly-specified play to the list.

## Stretch Goal

3. Earlier you wrote a component that retrieved data from a server via an HTTP request, using `HttpClient`. Refactor this so that the UI component is shielded from knowing where the data comes from by adding an intervening service:

        Component -> DataService -> HttpClient

Verify that it works in the browser.

4. Write a test for this intervening service. You will need to mock out the `HttpClient`.
