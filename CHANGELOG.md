2.0.2 
  - Add License file
  - Fix travis tests config
  
2.0
 - PHP >=7.1 branch without legacy support
 
1.3 
 - Added support for old php 5.6, php 7.0 versions

1.2
 - Window suppor improvement
 
1.1.1

   - Fix #13, use DIRECTORY_SEPARATOR constants for windows support
   - add tests for php 7.3 in travis.ci
   - move Changelog in separated file
   
1.1
   - Fix #10 - php extensions should be skipped without warnings

   - Fix #12 - check presence of scanner_config.php in current working directory and allow run without arguments

   - New config option - skipPackages for excluding packages from checking
      
1.0.9 
  - Add ability for store usage report [@see](https://github.com/Insolita/unused-scanner/blob/master/scanner_config.example.php#L51)


1.0.8 

- Return different exitCodes [@see](https://github.com/Insolita/unused-scanner/blob/master/Lib/Runner.php#L18)
