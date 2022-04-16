#ML/AI Course Berkeley

“Will a customer accept the coupon?” The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

Jupyter Notebook

The file contains visualization and solution of whether customer is accepting a coupon or not. The Jupyter notebook uses a data file in data directory.

Results

- The acceptance rate of people that go to bars more than once a month and are under the age of 30 is **higher** than people that go to bars more than once a month and were not kid and widowed
- The acceptance rate of people that go to bars more than once a month and are under the age of 30 is **higher** than people that go to cheap restaurants more than 4 times a month and income is less than 50K
- The acceptance rate of people that go to cheap restaurants more than 4 times a month and income is less than 50K is **higher** than people that go to bars more than once a month and were not kid and widowed
