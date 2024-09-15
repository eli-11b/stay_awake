<#
    .SYNOPSIS
        stay_awake

#>

$Time = 0
While($true){
    $KeepAlive = New-Object -com "wscript.shell"
    $KeepAlive.sendkeys(" ")
    Start-Sleep -Seconds 300
    $Time += 300
    Write-Host "Time Elapsed (Minutes):" ($Time/60) -ForegroundColor Yellow
} 
