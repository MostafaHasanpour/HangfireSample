# HangfireSample in ASP NET CORE

Create Your Database In Sql Server

...

    CREATE DATABASE HangfireSampleDb
    GO
...

then configure your project like my sample project

* Add Hangfire Packages from NuGet Package Manager

...

    * Hangfire
        1. Hangfire.Core
        2. Hangfire.AspNetCore
        3. Hangfire.SqlServer

* you must modified 

  1. startup
  2. appsetings.json
  3. your scheduler Action or Methode

![output in kesterel Console](https://github.com/MostafaHasanpour/HangfireSample/blob/master/screenshot.PNG)
