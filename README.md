# Shipping Packages Logic Puzzle

> This is a bonus assignment. Complete it at your own pace.

Model the problem and solve this [Shipping Packages logic puzzle] using
JavaScript. This puzzle can be solved incrementally with learning value at each
step in the solution. If you have not yet learned a concept listed in a step
below, feel free to work on only the steps you understand. We will eventually
learn everything you need in order to solve the whole puzzle.

Please put your solution in a GitHub repo called `shipping-packages-logic-puzzle`.

This exercise does not require running JavaScript in the browser. You can create
a `main.js` file in the root of your repo and run it on the command line using
[Node.js]:

```sh
node main.js
# your solution should print here using console.log statements
```

[Shipping Packages logic puzzle]:http://www.puzzlersparadise.com/onlinelogic/ShippingPackages.htm
[Node.js]:https://nodejs.org/en/

## Step #1

Model the data used in the puzzle. What are some good variable names for this
data? What data type(s) can you use to represent this data? Arrays, Strings,
Booleans, Objects, etc.

The possible first names are: Ellen, Heather, Rick, Walter

The possible last names are: Bartley, DeForest, Fairview, Gray

The possible states are: Ohio, Montana, Texas, Washington

The possible events are: anniversary, birthday, house warming, wedding

The possible relationships are: cousin, father, friend, sister

## Step #2

What logical statements can you use to model the six rules of the puzzle? Don't
worry about whether the variables you use exist or not, just focus on the logic
of the statements. If you had a magic wand and could create any function that
you need, what might the names of those functions be? How would you call them?

For example:
```js
// "Suzy's street name was not Merry Lane, but she did have a Golden Retriever."
if (streetName !== 'Merry Lane' && dogType === 'Golden Retriever') {
  maybeSuzy = true
}
```

## Step #3

Connect your data types with your logical statements in order to solve the
puzzle. Use `console.log` to print [the solution] as sentences like so:

> Heather Bartley lives in Ohio and is Greg's sister. She had a birthday on Thursday.

This is the hardest step of the puzzle. Note that you may need to change how you
model the data or your logical statements in order to create the solution. What
do you keep the same? What do you change? Why? Is there any temporary /
intermediate data that you need to create in order to get closer to the
solution? How can you tell if you are on "the right track" as you are working
toward the solution?

[the solution]:http://www.puzzlersparadise.com/onlinelogic/ShippingPackages/ShippingPackagesSol.htm

## Problem Description

Yesterday, Greg was very busy packing up some gifts to send out to family and
friends. It was a busy month. He had a birthday, an anniversary, a wedding, and
even a house warming to send gifts out for - and the events all took place in
the same week! Because he moved away from his home area when he took his new
job, he lived across the country from most of his family and friends now. As a
result, he always tried to find something locally for each person to make each
gift more personal and interesting. Determine the full name of each person he
shipped a gift to, what state each lived in, what each event was, each person’s
relationship to Greg, and what day of the week each event was taking place
(Wednesday through Saturday).

1. Greg’s friend wasn’t Ellen Fairview, who didn’t live in Ohio. The birthday girl didn’t have her party on Friday.
2. Rick’s last name wasn’t Bartley but his event was on Saturday night.
3. Greg’s father wasn’t getting married, but his last name was Gray.
4. The friend having a house warming didn’t live in Ohio.
5. The wedding was for Greg’s cousin.  Heather, who didn’t live in Texas, was Greg’s sister but her event wasn’t on Wednesday night.
6. Walter’s event was one day earlier than the person whose last name was DeForest but after the person
   who lived in Washington. The anniversary was held in Montana.

## Hints

Below are some hints for solving the puzzle. They are in order of the typical
progression of solving the puzzle. I do not recommend looking at more than one
hint at a time. If you are stuck, take a look at Hint #1, then give it a think
for at least a day, then look at Hint #2, etc. The last hint is very revealing
of the solution.

The hints are encoded using [Base64](https://www.base64decode.org/).

#### Hint 1 - If you do not know where to start.

```txt
Q3JlYXRlIGFsbCBvZiB0aGUgcG9zc2libGUgb3B0aW9uIGNvbWJpbmF0aW9ucy4gSG93IGNhbiB5b3UgZG8gdGhhdD8gSG93IG1hbnkgdG90YWwgcG9zc2libGUgb3B0aW9ucyBhcmUgdGhlcmU/IFdoYXQgaXMgYSBnb29kIGRhdGEgc3RydWN0dXJlIHRvIHJlcHJlc2VudCBhbiBvcHRpb24/
```

#### Hint 2 - Logic rules 1

```txt
V2hpY2ggb2YgdGhlIG9wdGlvbnMgY2FuIHlvdSBydWxlIG91dCBiYXNlZCBvbiB0aGUgNiBwdXp6bGUgcnVsZXM/IEhvdyBtYW55IGNhbiB5b3UgcnVsZSBvdXQ/
```

#### Hint 3 - Logic rules 2

```txt
U29tZSBvZiB0aGUgb3B0aW9ucyBjYW4gYmUgcnVsZWQgb3V0IGluZGl2aWR1YWxseSwgb3RoZXJzIGFyZSBpbnZhbGlkIHJlbGF0aXZlIHRvIG90aGVyIG9wdGlvbnMuIEhvdyBjYW4geW91IG1vZGVsIHRoZSBkYXRhIGluIG9yZGVyIHRvIHRlc3QgYSBydWxlIGxpa2U6ICJXYWx0ZXIncyBldmVudCB3YXMgb25lIGRheSBlYXJsaWVyIHRoYW4gdGhlIHBlcnNvbiB3aG9zZSBsYXN0IG5hbWUgd2FzIERlRm9yZXN0IiA/
```

#### Hint 4 - Function and variable names used in a solution.

> Note: This hint is very revealing. Only decode it if you are totally stuck after Hint #3.

```txt
TODO: add this hint
```

## License

[ISC License](LICENSE.md)
