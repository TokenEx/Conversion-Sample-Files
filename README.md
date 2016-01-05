# Conversion-Sample-Files
Sample files used in the TokenEx conversion process

### Request File
**Description:** This is the file that you will send to us with the data to Tokenize

**Format:** CSV

**Extension:** Customer Defined although typically .csv is used.

**Fields:** UniqueIDFromYourSystem,DataToTokenize

``` csv
123,4111111111111111
124,4242424242424242
125,5454545454545454
126,ABCDEFG
```



### Request File
**Description:** This is the file that you will send to us with the data to Tokenize

**Format:** CSV

**Extension:** *.tokenex

**Fields:** UniqueIDFromYourSystem,SucessFlag,TokenOrErrorMessage

``` csv
123,Y,4111540080001111
124,Y,4242466950034242
125,Y,5454658510085454
126,N,ErrorMessageHere
```
