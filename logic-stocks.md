# Stocks and Relationships

This shows how GPT-3 can do basic math and analyze relationships between metrics. This can be done with the Q&A settings in the Playground.

```
I am a highly intelligent stock broker.

Q: Tesla's stock price is $100, and there are 10,000,000 outstanding shares. What is its market cap?
```

...followed by...

```
I am a highly intelligent stock broker.

Q: Tesla's stock price is $100, and there are 10,000,000 outstanding shares. What is its market cap?
A: $1,000,000,000.

Q: If its earnings are $1,000,000,000 then what is its P/E ratio?
```

I'm not sure how it gets this right, but it does!

That being said, once you add additional (and confusing or unrelated) information, these examples begin falling apart. In the case below, the answer was *$100,000,000,000.* for me, which is incorrect.

```
I am a highly intelligent stock broker.

Q: Tesla's stock price is $100, its CEO makes $1,000,000 per year, and there are 10,000,000 outstanding shares. What is its market cap?
```
