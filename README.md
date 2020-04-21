# American Sign Language Model Builder App

The application is a full-stack ASP.NET Core web application that uses input from a user's camera to classify images to one of the letters of the American Sign Language alphabet.

## About the application

- **ASLModelBuilderAPI**: Back-end ASP.NET Core Web API that hosts the Machine Learning model and makes predictions.
- **ASLModelBuilderML.ConsoleApp**: .NET Core console application for testing out the model and quickly making predictions. (Autogenerated)
- **ASLModelBuilderML.Model**: .NET Standard class library that contains generic code for consuming the model. (Autogenerated)
- **ASLModelBuilderWASM**: Front-end Blazor Web Assembly application to capture images from the user.

## Run the application

1. Set the `ASLModelBuilderAPI` project as your startup project and start the application.
1. In the Visual Studio solution explorer, right-click the `ASLModelBuilderWASM` project and select **Debug > Start New Instance**. 
1. Once the browser opens the Blazor application, navigate to the `/camera` page.

## Additional Resources

- [ML.NET Documentation](https://docs.microsoft.com/dotnet/machine-learning/)
- [ML.NET YouTube Playlist](https://www.youtube.com/watch?v=pxUzw6JyqcM&list=PL1rZQsJPBU2TwElfOzqOsUW1yuxKNA091)
- [ML.NET Samples](https://github.com/dotnet/machinelearning-samples)
- [ML.NET GitHub Repo](https://github.com/dotnet/machinelearning)