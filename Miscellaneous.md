Miscellaneous
=============

## Useful in .csproj

  ```xml
    <LangVersion>8.0</LangVersion>
    <Nullable>enable</Nullable>
    <WarningsAsErrors>CS8600;CS8602;CS8603;CS8632;CS8669</WarningsAsErrors>
  ```
  
  - CS8600: Converting null literal or possible null value to non-nullable type.
  - CS8602: Dereference of a possibly null reference.
  - CS8603: Possible null reference return.
  - CS8632: The annotation for nullable reference types should only be used in code within a '#nullable' annotations context.
  - CS8669: The annotation for nullable reference types should only be used in code within a '#nullable' annotations context. 
            Auto-generated code requires an explicit '#nullable' directive in source.