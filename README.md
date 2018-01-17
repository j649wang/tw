Solution
====================
Author: JW
---------------------

One possible solution for homework is provided in 'answer_v2.py'.

Here are two aspects to ensure the correctness of the solution.
### Run tests through main function
In main function, set test file as signal content. Check the outputs 
printed on console in different cases. Example codes are as follows.
> signal = signals(content='more_planes.txt')
> 
> print(signal.signalIndex(6))
>
> plane2 6 4 6 1

### Use unittest
Refer to 'test_v2.py' as an example for unittest.
To run the suite of tests, do the following command.
> python test_v2.py

Results： 
> Ran 4 tests in 0.008s
>
> OK
