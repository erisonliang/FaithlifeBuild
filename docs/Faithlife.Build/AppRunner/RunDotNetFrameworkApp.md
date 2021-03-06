# AppRunner.RunDotNetFrameworkApp method (1 of 3)

Runs the specified .NET Framework command-line app.

```csharp
public static int RunDotNetFrameworkApp(string path, AppRunnerSettings settings)
```

| parameter | description |
| --- | --- |
| path | The path of the command-line app. |
| settings | The settings to use when running the app. |

## Remarks

On Linux and macOS, Mono is used to run the app.

## See Also

* class [AppRunnerSettings](../AppRunnerSettings.md)
* class [AppRunner](../AppRunner.md)
* namespace [Faithlife.Build](../../Faithlife.Build.md)

---

# AppRunner.RunDotNetFrameworkApp method (2 of 3)

Runs the specified .NET Framework command-line app.

```csharp
public static void RunDotNetFrameworkApp(string path, IEnumerable<string> args)
```

| parameter | description |
| --- | --- |
| path | The path of the command-line app. |
| args | The arguments to send to the command-line app. |

## Remarks

On Linux and macOS, Mono is used to run the app.

## See Also

* class [AppRunner](../AppRunner.md)
* namespace [Faithlife.Build](../../Faithlife.Build.md)

---

# AppRunner.RunDotNetFrameworkApp method (3 of 3)

Runs the specified .NET Framework command-line app.

```csharp
public static void RunDotNetFrameworkApp(string path, params string[] args)
```

| parameter | description |
| --- | --- |
| path | The path of the command-line app. |
| args | The arguments to send to the command-line app. |

## Remarks

On Linux and macOS, Mono is used to run the app.

## See Also

* class [AppRunner](../AppRunner.md)
* namespace [Faithlife.Build](../../Faithlife.Build.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Build.dll -->
