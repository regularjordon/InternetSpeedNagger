# InternetSpeedNagger
#### Nagging at internet service providers since 2018.

25/05/2018: This project got featured in [Import Python](http://importpython.com)!

***

## How to run InternetSpeedNagger.py
1. Go to [Twitter Apps](https://apps.twitter.com/) and register an application.
2. Clone this repository.

  `$ git clone https://github.com/crlsmnzs/InternetSpeedNagger`
  or download as a ZIP.

3. Open a terminal window in the location you cloned/extracted the repository to and install the modules in `requirements.txt`.

  `pip install -U -r requirements.txt`

4. Open `InternetSpeedNagger.py` and edit the first four variable values with information from the application you registered in step 1.
5. Change other information you deem necessary.


**If your internet speed is higher than 100MB/s, you might want to change these lines:**

  ```python
  dSpeed = dSpeed[0][0:2] + '.' + dSpeed[1][0:2]
  uSpeed = uSpeed[0][0:2] + '.' + uSpeed[1][0:2]
  ```

**to**

  ```python
  dSpeed = dSpeed[0][0:3] + '.' + dSpeed[1][0:2]
  uSpeed = uSpeed[0][0:3] + '.' + uSpeed[1][0:2]
  ```
**in order to encapsulate the first 3 digits.**

*** 


