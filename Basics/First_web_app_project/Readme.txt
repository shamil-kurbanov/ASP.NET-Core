dotnet new webapp -o aspnetcoreapp

The preceding command:

Creates a new web app.
The -o aspnetcoreapp parameter creates 
a directory named aspnetcoreapp
with the source files for the app.


#Trust the development certificate
dotnet dev-certs https --trust

Run the app

-> cd aspnetcoreapp
-> dotnet watch run

After the command shell indicates that the 
app has started, browse to https://localhost:{port}, 
where {port}is the random port used.

