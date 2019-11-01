# .Net GraphQL

If you're new to GraphQL, check out these videos featured in the [Learn More](#learn-more) section, below
- [Learning GraphQL Series](#learning-graphql-series)
- [Xamarin + GraphQL](#xamarin--graphql)

To run this sample, follow the [Getting Started Instructions, below](#getting-started).

This app was featured at [GraphQL Summit 2019](https://codetraveler.io/GraphQLSummit-DotNet).

### GraphQL Backend
The GraphQL backend is created in C# using the [GraphQL NuGet Package](https://www.nuget.org/packages/GraphQL/).

| GraphiQL |
| -------- |
| ![GraphiQL](https://user-images.githubusercontent.com/13558917/67914743-3a8f4700-fb4e-11e9-936d-320dfdd5d874.png) |

### Mobile
The mobile app is created in C# using [Xamarin](https://docs.microsoft.com/xamarin/cross-platform/?WT.mc_id=DotNetGraphQL-github-bramin) and the [GraphQL.Client NuGet Package](https://www.nuget.org/packages/GraphQL.Client/).

| Xamarin.iOS | Xamarin.Android |
| ----------- | --------------- |
| <img src="https://user-images.githubusercontent.com/13558917/67914056-44b04600-fb4c-11e9-98ee-9d7ecb1bbc65.png" height="600"> | <img src="https://user-images.githubusercontent.com/13558917/67915040-16803580-fb4f-11e9-80c2-ae91a25f4e7b.png" height="550"> | 

## Getting Started

This app requires us to run the GraphQL API using the terminal while using Visual Studio to build/deploy the Xamarin.iOS and/or Xamarin.Android app.

### Run the GraphQL API

1. Open the **terminal**
2. In the **terminal**, clone this solution by entering the following command:
    - **Note:** If you have already downloaded the solution, skip this step

```bash
git clone https://github.com/brminnick/dotnetgraphql.git
```

3. In the **terminal**, navigate to the `DotNetGraphQL.API` folder by entering the following command:

- On Windows

```bash
cd [path to DotNetGraphQL folder]\Source\DotNetGraphQL.API\
```
- On macOS
```bash
cd [path to DotNetGraphQL folder]/Source/DotNetGraphQL.API/
```

4. In the **terminal**, run `DotNetGraphQL.API.csproj` by entering the following command:

```bash
dotnet run
```

5. Open a web browser
6. In the web browser, navgiate to `http://localhost:4000`
7. Confirm GraphiQL

### Run the Xamarin.Android App

1. In **Visual Studio**, open `DotNetGraphQL/Source/DotNetGraphQL.sln`
2. In **Visual Studio**, in the **Solution Explorer**, right-click on **DotNetGraphQL.Android**
3. In the right-click menu, select **Set as Startup Project**
4. In **Visual Studio**, build/deploy **DotNetGraphQL.Android** to an Android device
6. Confirm the list of dogs from the GraphQL API appears

# Learn More

Learn more about Xamarin + GraphQL

## Docs

### Xamarin Resources

- [Getting Started with Xamarin](https://docs.microsoft.com/xamarin/cross-platform/?WT.mc_id=DotNetGraphQL-github-bramin)
- [Getting Started with Xamarin.Forms](https://docs.microsoft.com/xamarin/xamarin-forms?WT.mc_id=DotNetGraphQL-github-bramin)
- [Install Visual Studio (PC) + Xamarin](https://docs.microsoft.com/xamarin/get-started/installation/windows?WT.mc_id=DotNetGraphQL-github-bramin)
- [Install Visual Studio for Mac + Xamarin](https://docs.microsoft.com/visualstudio/mac/installation?view=vsmac-2019&WT.mc_id=DotNetGraphQL-github-bramin)
- [Microsoft Learn: Build Mobile Apps With Xamarin.Forms](https://docs.microsoft.com/learn/paths/build-mobile-apps-with-xamarin-forms?WT.mc_id=DotNetGraphQL-github-bramin)
- Xamarin Source Code
    - [Xamarin.iOS](https://github.com/xamarin/xamarin-macios)
    - [Xamarin.Android](https://github.com/xamarin/xamarin-android)
    - [Xamarin.Forms](https://github.com/xamarin/Xamarin.Forms)
    - [Mono](https://github.com/mono/mono)
    
### GraphQL Resources

- [GraphQL.org](https://graphql.org/)
- [Using Postman with GraphQL API](https://www.codetraveler.io/2019/01/12/how-to-use-postman-with-a-graphql-api/)
- [GraphQL for .NET](https://github.com/graphql-dotnet/graphql-dotnet)
- [GraphQL vs REST](https://philsturgeon.uk/api/2017/01/24/graphql-vs-rest-overview/)
- [GraphQL vs OData](https://jeffhandley.com/2018-09-13/graphql-is-not-odata)
- [Awesome GraphQL](https://github.com/chentsulin/awesome-graphql)

## Video Recordings

### Xamarin + GraphQL

The session on Xamarin + GraphQL was delivered at [Xamarin Developer Summit 2019](https://www.codetraveler.io/xamdevsummit-graphql/) and its recording is available on YouTube: https://youtu.be/t1cQsenAmNo?t=18575

[![Xamarin + GraphQL Video](https://user-images.githubusercontent.com/13558917/61256668-6a8f1780-a722-11e9-97ad-8188ec6eab8f.png)](https://channel9.msdn.com/Events/Xamarin/Xamarin-Developer-Summit-2019/XamarinGraphQL?WT.mc_id=DotNetGraphQL-github-bramin)

### Learning GraphQL Series

This special series teaches the basics of GraphQL, how to interact with an existing GraphQL endpoint, how to create your first GraphQL Server, and how to deploy your GraphQL Server to the cloud using Azure! 

[![Learning GraphQL Series](https://sec.ch9.ms/ch9/167c/d62bfc00-95ae-42a1-ab23-af9b9602167c/IntrotoGraphQL_512.jpg)](https://channel9.msdn.com/Series/GraphQL?WT.mc_id=DotNetGraphQL-github-bramin)
