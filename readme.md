![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | TS Koans Advanced

## Koans

![](https://i.imgur.com/9Ug9NBn.png)

```
Two monks were arguing on top of a hill about a big
flag at the top of a temple. One monk reflected:

> "The flag is moving"

The other thought for a while and said:

> "The wind is moving.".

The sixth patriarch happened to be passing by.

He told them:

> "Not the wind, not the flag; The mind is moving."
```

<br>

### What are the Koans?

[Koans](https://en.wikipedia.org/wiki/K%C5%8Dan) (公案) originate from Zen Buddhism, and are paradoxical riddles or stories used to test "students" on their path to enlightenment. They are designed to provoke thought or doubt in the student's mind. We are here to learn to code, so... what are the Koans?

The Koans are a series of assertions you must solve to understand how a programming language works. This is the first step to become a better developer. The Koans become increasingly more difficult as you continue, so don't feel discouraged as you move forward through them.

There are Koans for all the programming languages. We will work with JavaScript Koans. The mechanism is the following:

- You get an assertion that is not passing a **test**.
- You have to give the test the correct expected result to pass it.

<br>



## Testing

When we are coding, we have to be sure that our code is working as we expect. More than that, when we update our existing code, we have to be 100% sure that our old code is still working. As our website becomes larger, it becomes more difficult to check that all our features are working as we expect. How can we automate this process? The answer is with **testing**.



Testing allows us to check if the full set of features we have build is working as we expect. Sometimes you can create new features that override or damage the old ones. We avoid this with testing.

<br>



### Anatomy of a test

The syntax to create a test depends on the framework we are using. So we will explain the basic anatomy of a test with [pseudocode](https://en.wikipedia.org/wiki/Pseudocode).



Given a function with some parameters, we expect to get a result. If the result is what we are expecting, the test will pass. If we get an unexpected result, the test will fail. The framework will show the tests that are passing in green, and the tests that are failing in red.

Let's suppose we have the following function:

```javascript
function add(num1, num2) {
  // ...
}
```

If we pass as parameters to the `add` function the numbers 1 and 2, we should get a 3 as a result. So we are calling the `add` function with two numbers, and we expect from the function to return us the sum of those numbers.

If we get 3 as a result, the test will pass. If we get any other result, the test will fail. In pseudo code, it would be something like this:

```
given the parameters 1 and 2 to the add function, we expect to get 3 as a result
```

This is the anatomy of a test. We have the knowledge to understand what is a test and how it works. Now we will introduce you to a JavaScript framework to test our application.

<br>

## Exercise

### Requirements

- Fork this repo

- Clone this repo

  

<br>

### Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m "Solved lab"
$ git push origin master
```

Create Pull Request so your TAs can check up your work.

<br>



### Instructions

We need to execute our tests. After you forked and cloned this repo, install the project dependencies.

```sh
npm i # or npm ci
```

In the beginning, you will see all the tests in green. This is because only the tests that are passing are un-commented. The tests we have to implement are commented out.

Open the `koans.spec.ts` file and uncomment the test assertions.

Unncommenting those assertions will give you a failing test that you need to make it pass.


** We want you to understand why each test is failing and how TypeScript works in different scenarios.**

To do that, the correct workflow is the one used on [TDD](https://en.wikipedia.org/wiki/Test-driven_development):

- Uncomment the test
- See that the un-commented test is failing
- Change the code to pass the test
- Refresh the page to see that the test is passing

> You should not have any ts error, if you see some when uncomenting code, analize it and commented it if necessary to avoid them.https://github.com/Jossdz/lab-ts-koans-advanced

This process has to be done for each test. **Do not uncomment all the tests and launch the app. It will be more difficult for you to see if your code is passing the tests.**

As we said, this is the first step to become a better developer.

Good luck to all of you and happy coding. ❤️