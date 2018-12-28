## 01 Startup

* UseDeveloperExceptionPage() This extension method displays details of exceptions that occur in the 
application, which is useful during the development process. It should not be enabled in deployed applications, and I disable this feature when I deploy the application in Chapter 12.
* UseStatusCodePages() This extension method adds a simple message to HTTP responses that would not otherwise have a body, such as 404 - Not Found responses.
* UseStaticFiles() This extension method enables support for serving static content from the wwwroot folder.
* UseMvc() This extension method enables ASP.NET Core MVC.