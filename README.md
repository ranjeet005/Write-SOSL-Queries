# Write-SOSL-Queries
Create an Apex class that returns both contacts and leads that have first or last name matching the incoming parameter.
The Apex class must be called ContactAndLeadSearch and be in the public scope
The Apex class must have a public static method called searchContactsAndLeads
The method must accept an incoming string as a parameter
The method should then find any contact or lead that matches the string as part of either the first or last name
The method should finally use a return type of List<List< SObject>>
