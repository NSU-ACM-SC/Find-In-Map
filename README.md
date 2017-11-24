# Address Finder in Map
#### Uses google maps to find supplied address and show it in a web browser

* Doesn't use any map api
* Unless google changes their base url system for google maps,
  this should work
* Need to improve the unit tests, so any contributions in this
  dept. are welcome!


#### Usage

* You can just copy the address to your clipboard and use the clipboard module
* Or you can pass the address as a command line argument while running the
  program.

  ```bash
  cd source_find_map
  python find_in_map.py <address>
  # you can use punctuation marks in the address, it's safe
  ```
