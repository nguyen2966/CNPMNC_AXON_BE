## Cho dev dùng VSCode
Dùng lệnh này chạy trong terminal để start app

```
Get-Content .env | ForEach-Object { if ($_ -match "^(.*?)=(.*)$") { [System.Environment]::SetEnvironmentVariable($matches[1], $matches[2]) } }; ./mvnw spring-boot:run
```

## Dev dùng IntelJ
Nạp biến env vào IntelJ


## Test plan được trình bày trong TestPlan.md