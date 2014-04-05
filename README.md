Real World Windows Azure - Article 2
=============

This is a sample application I wrote for the "Real World Windows Azure"-Series in the Windows Developer Magazine.

Installation:
-------------
1. Create a windows azure subscription. See: http://www.windowsazure.com/de-de/pricing/free-trial/
2. Create a windows azure service bus account. See: http://azure.microsoft.com/en-us/documentation/articles/service-bus-dotnet-how-to-use-relay/
3. Copy the service bus address to the "Server"- and "Client"-Project app.config files.
4. Go to the "configure" tab and create two shared access policies: one for "Send" and one for "Listen".
5. Enter the "Listen" credentials to the app.config of the "Server"-Project and the "Send" Credentials to the app.config of the "Client"-Project.
6. Run Server and Client Project


![Configuration](rolandkru.github.com/rwwa-article2/configuration.png)
