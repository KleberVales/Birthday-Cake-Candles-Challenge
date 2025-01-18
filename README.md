# 🎂 Birthday Cake Candles Challenge

## 📝 Challenge Description
In the Birthday Cake Candles challenge, you are given a list of candles, where each candle’s height represents a child's age. The child can only blow out the tallest candles. Your task is to count how many candles have the maximum height.

## 📥 Input Format
- The first line contains an integer n, the number of candles.
- The second line contains n space-separated integers, representing the height of each candle.

## 📤 Output Format
- A single integer representing the number of tallest candles that can be blown out.

## ✅ Example

### Input:
```java

4
3 2 1 3

```
### Output:
```java

2

```
## 🔍 Explanation
- The given candle heights are 3, 2, 1, 3.
- The maximum height is 3.
- There are two candles with this height, so the output is 2.

## 🚀 Function Signature
``` java

int birthdayCakeCandles(List<Integer> candles)

```
- Parameters: A list of integers representing candle heights.
- Returns: An integer indicating the count of the tallest candles.
