# SMS Lite Static Demo

URL: https://eshagupta-usda.github.io/SMSLiteDemoPages/

Static Blazor WebAssembly demo for GitHub Pages. The deployable app uses browser-side in-memory data and local storage only. It does not require `SMSLiteStaticDemo.Server`, API endpoints, databases, or external service calls.

## Deploy To GitHub Pages

The workflow publishes `SMSLiteStaticDemo/SMSLiteStaticDemo.csproj` and deploys `publish/wwwroot` to GitHub Pages over HTTPS.

## Local Preview

```bash
dotnet run --project SMSLiteStaticDemo/SMSLiteStaticDemo.csproj
```

Open the URL printed by the command. The app is still fully static at runtime; the dev server is only for local preview.
