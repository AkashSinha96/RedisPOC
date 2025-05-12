# Use the official .NET runtime image for the runtime environment
FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS base

# Set the working directory in the container
WORKDIR /app

# Copy the published output from the out directory
COPY out .

# Specify the entry point for the application
ENTRYPOINT ["dotnet", "RedisPOC.dll"]