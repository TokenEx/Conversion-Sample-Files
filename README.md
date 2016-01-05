# Conversion-Sample-Files
Sample files used in the TokenEx conversion process

### Request File
**Description:** This is the file that you will send to us with the data to Tokenize. The file should contain a unique identifier from your system as well as the data to Tokenize.

**Format:** CSV

**Extension:** Customer Defined although typically .csv is used.

**Fields:** UniqueIDFromYourSystem,DataToTokenize

``` csv
123,4111111111111111
124,4242424242424242
125,5454545454545454
126,ABCDEFG
```



### Response File
**Description:** This is the file that you will send to us with the data to Tokenize. The file will contain your unique identifier as well as a success flag and the token. If the success flag is "N", then there will be a human readable error message in place of the token.

**Format:** CSV

**Extension:** *.tokenex

**Fields:** UniqueIDFromYourSystem,SucessFlag,TokenOrErrorMessage

``` csv
123,Y,4111540080001111
124,Y,4242466950034242
125,Y,5454658510085454
126,N,ErrorMessageHere
```
