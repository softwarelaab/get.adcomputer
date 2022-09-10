# get adcomputer

[![get adcomputer](gett-stateed.png)](https://github.com/softwarelaab/get.adcomputer)

The Get-ADComputer cmdlet gets a computer or performs a search to retrieve multiple computers. The Identity parameter specifies the Active Directory computer to retrieve. You can identify a computer by its distinguished name (DN), GUID, security identifier (SID) or Security Accounts Manager (SAM) account name.

## How to use Get-ADComputer in PowerShell

Need to export all computers from an OU, or lookup a computer in your Active Directory? Or do you want to count how many computers you have? We can use the Get-ADComputer cmdlet in PowerShell to quickly extract computer information from the AD.

The Active Directory contains all the computers that are member of our domain. The management console is great to look up a single computer. But when you want to get details of single or multiple computers, then we need to use PowerShell.

## Finding Computers with Get ADComputer in PowerShell

_The Get-ADComputer cmdlet allows us to find computer objects in the Active Directory and extract information from them. The true power of this cmdlet is that it comes with different options to find those computer objects._

**We have the following options when it comes to finding objects:**

* Identity – Find computers based on their name. This will return only a single computer
* Filter – Retrieve multiple objects based on a query
* LDAPFilter – Use a LDAP query string to filter the computer objects
* SearchBase – Specify the Active Directory path (OU) to search in
* SearchScope – Specify how deep you want to search (base level, one level, or complete subtree)

##How do I get ADComputer?

* Install Active Directory Module.
* Finding Computers with Get ADComputer in PowerShell.
* Get ADComputer SearchBase.
* Using the SearchScope.
* Using the Filter parameter. Get Computers based on OS.
* Get ADComputer Properties.
* Export AD Computer to CSV with PowerShell.
* Wrapping Up.
