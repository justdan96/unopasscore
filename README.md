# PassCore 1.0

## Project Description

PassCore is a very simple 1-page web app written in C#, using ASP.NET MVC 4 and Directory Services. It allows users to change their Active Directory password on their own, provided the user is not disabled.

PassCore does not require any configuration, as it obtains the principal context from the current domain. I wrote this in less than 2 hours. There really was no free alternative out there so hopefully this saves someone else some time and money.

IMPORTANT: If you are going to expose this web app outside your LAN, please use https

## Installation Instructions

Installation instructions for non-developers/sys admins:

1. Extract the files to a folder. (go to the Releases section and get the zip file)
2. Move the resulting folder to the path where your IIS sites reside
3. Go to IIS and add the folder as a site. Make sure the Application Pool is a .NET 4/Integrated Pipeline App Pool and that the bindings are properly configured.

## Archive Status

(justdan96): Due to issues around the longevity of CodePlex I am providing the original code here along with the 1.0 binary release. For the very latest PassCore releases please go to http://github.com/unosquare/passcore.
