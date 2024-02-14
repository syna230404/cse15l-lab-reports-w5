# Lab Report 5

## Buggy Code

![Image](Screenshot 2024-02-13 at 22-05-23 Team Snake Lab 4.png)

## JUnit Test Fail

```
@Test
public void reveredBig() {
  int [] input = {1,2,3};
  asserEquals(new int[] {3,2,1}, ArrayExamples.reversed(input));
}
```

## JUnit Test Pass

```
@Test
public void reveredSmall() {
  int [] input = {1};
  asserEquals(new int[] {1}, ArrayExamples.reversed(input));
}
```

