- principle: the purpose of all programs, and all parts of programs, is to transform data from one form to another
- if you don't understand the data, you don't understand the problem, and vice versa
- if you don't understand the hardware, you can't reason about the cost of solving the problem
- everything is a data prob. including usability, maintenance,...
- solving probs you don't have creates more probs you do
- reason must prevail
### lies
- software isn't the platform, it's hardware
- code designed around model of the world. confuses two problems:
	- maintenance (allow changes to access)
	- understanding properties of data: critical for solving problems
	- world modeling leads to monolithic, unrelated data structures & transforms
	- world modeling tries to idealize the prob
	- world modeling is the equi. of self-help books for programming, by analogy/story-telling lmao ain't it not the truth
- code is more important than data
### purpose
- only purpose of code is to transform data from one form to the other
- programmer's job is not to write code, but to solve (data transformation) probs
- only write code that has direct, provable value, ie transforms data in meaningful way
### what to do?
- solve for transforming the data you have given the constraints of the platform
	- damn this sounds so similar to the way a problem in positive/descriptive econ is framed!!!
- eg: dict of key & value: storing everything isn't efficient, bc most of the time most values aren't being retrieved. 
	- solve for the most common case first, not the most generic one: model around the data-generating process instead
