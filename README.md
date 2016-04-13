# interview-baidu

Some time ago, I received an exercise from Baidu's [artificial intelligence labs](http://research.baidu.com/),
 for a software engineer role. Sadly, it sat in my junk folder for a few days
 longer than the due date. However, in the spirit of fun, I attempted the
 challenge via C++. The [job description](https://github.com/jeff1evesque/interview-baidu/blob/master/position.md)
 mentioned that C++ was a requirement. Apparently, the clock keeps ticking,
 even though you didn't click proceed to the second half of the interview (i.e. [coding exercise](https://github.com/jeff1evesque/interview-baidu/blob/master/exercise/challenge.md#section-2-coding-challenge-50-minutes)).
 Nevertheless, it was fun having never programmed in C++ (reason why I'm uploading this).

## Configuration

### GIT

Fork this project in your GitHub account, then clone your repository:

```
cd /var/www/
sudo git clone https://[YOUR-USERNAME]@github.com/[YOUR-USERNAME]/interview-baidu.git
```

Then, change the *file permissions* for the entire project by issuing the command:

```
cd /var/www/interview-peloton/
sudo chown -R jeffrey:sudo interview-baidu
```

**Note:** change 'jeffrey' to the user account YOU use. 

## Exercise

This repository provides the following files:

- [`position.md`](https://github.com/jeff1evesque/interview-baidu/blob/master/position.md):
 the software engineering job description.
- [`sample-challenge.md`](https://github.com/jeff1evesque/interview-baidu/blob/master/exercise/sample-challenge.md):
 an example of what to expect for the coding exercise portion of the interview.
- [`challenge.md`](https://github.com/jeff1evesque/interview-baidu/blob/master/exercise/challenge.md):
 the actual exercise portion given.
- [`starting_point.cpp`](https://github.com/jeff1evesque/interview-baidu/blob/master/exercise/starting_point.cpp):
 the provided script for the second half of the interview, required for the
 second half of the interview (i.e. coding exercise).