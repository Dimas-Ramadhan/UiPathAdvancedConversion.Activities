# UiPathAdvancedConversion.Activities

AdvancedConversion.Activites are used to convert several datatypes which has value to another datatypes with return new value. from UiPath application. In order to use these activities they must give attention to an input and output arguments.

Pre-requisites - there is no pre-requisite.

## Activities
1. DataTable to HTML
2. Number to Alphabet
3. Number to Indonesian Rupiah
4. Number to Roman

## DataTableToHTML
This Activity used for convert datatable type to string of datatable in HTML format.
### Input fields
-DataTable : your DataTable variable
-StyleCSS : CSS for the datatable in string formay, example "<style>table, td, th {border: 1px solid;}</style>"

## NumberToAlphabet
This activity will convert number to return an Alphabet in excel, which means after X,Y, Z it will comes to AA, AB etc.
example: number = 1 will return alphabet = A , 27 will return AB
### Input fields
-Number : Number index you want to convert, in Int32 or Int64 type.

## NumberToIndonesianRupiah
This activity will convert number in Int format to a spelling Indonesian Rupiah in String type, example: 10300 will return "sepuluh ribu tiga ratus rupiah"
### Input fields
-Number : Number index you want to convert, in Int32 or Int64 type.

## NumberToRoman
This activity will convert Number to Roman string. example 6 will return VI
### Input fields
-Number : Number index you want to convert, in Int32 or Int64 type.
