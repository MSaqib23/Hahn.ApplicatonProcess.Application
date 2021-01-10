# Hahn.ApplicatonProcess.Application

Steps

1. Extract file Hahn.Solution.rar
2. Insie Hahn.Solution folder 
Hahn.ApplicatonProcess.Application ( .Net 5 Core Web API )
Hahn.ApplicationProcess.AureliaUI

3. Hahn.ApplicatonProcess.Application contains
	Hahn.ApplicatonProcess.December2020.Data  ( restore dotnet packages . EF Core Inmemory Database )
	Hahn.ApplicatonProcess.December2020.Domain ( business logics and DTO models )
	Hahn.ApplicatonProcess.December2020.Web ( Web Api controller actions)
	Hahn.ApplicatonProcess.Application.sln ( Solution file )
Open the solution with .sln file and build and run after restore dotnet packages )
It will open browser with 
http://localhost:5000/swagger/index.html

Here you can test all API's 
http://localhost:5000/api/Applicant/GetAll  ( it wil return 2 predefined Applicant response )
http://localhost:5000/api/Applicant/Get/2   ( get the specific id applicant profile )
http://localhost:5000/api/Applicant/Add     ( post to save applicant profile if successfull)
http://localhost:5000/api/Applicant/Update/2 ( put to update applicant profile of selected applicant id)
http://localhost:5000/api/Applicant/Delete/2  ( Delete selected id applicant profile )
http://localhost:5000/api/Applicant/GetAllCountries ( get all countries name against https://restcountries.eu/rest/v2/all)

4. Hahn.ApplicationProcess.AureliaUI contains
	front end application which calling backend api to view Applicant profile.

Things which is not covered.
1. Validation on Aurelia forms.
2. Aurelia-I18N localization and internationlization features
3. Bundling via Webpack
4. Dialog Box for popping messages.




