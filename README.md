# Load Testing Using K6

We are using https://fakerestapi.azurewebsites.net/index.html for tests

There are 4 main types of Performance Tests:

1) Load Testing
2) Soak Testing
3) Spike Testing
4) Stress Testing

# To run tests locally:

```
git clone https://github.com/chiragverma/load-testing.git
```

```
cd load-testing
```

# Install K6:

```
brew install k6
```

# To run tests:

```
k6 run simple_test.js
```
