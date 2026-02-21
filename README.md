# Blazor Blueprint Testing

> This project is a testing playground for the Blazor Blueprint library, which provides a set of reusable UI components for building web applications with Blazor.

> https://blazorblueprintui.com/

## Project Technical Details


| Aspect | Description
|---|---|
| .Net Framework  | 8.0 | 
| Render Mode | Server | 

> Project Initialization command: 
```bash
dotnet new blazorblueprint -n MyApp -F net8.0 -R Server
``` 



## Current Problem
I cannot get the sidebar to be visible for some reason. It is not rendering on the UI

I have tried to use the [`Sidebar`](https://blazorblueprintui.com/docs/components/sidebar) component from the Blazor Blueprint library, but it does not appear on the page. I have checked the documentation and examples, but I cannot find a solution to this issue.

When all went south, I went for the nuclear option of copy-pasting the code from the [Task Manager](https://blazorblueprintui.com/blueprints/apps/app-tasks) blueprint. Still, the sidebar did not show up. I am not sure if this is a bug in the library or if I am missing something in my implementation.