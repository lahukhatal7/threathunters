# Trufflehog

Use this query to look for Trufflehog tool in the environment.

## EDR CDM [Cloud Console queries]

### Search for Trufflehog tool launch

```
Device OS Type:100-Windows AND Event Type Id: 8001-Process Activity AND Disposition:1 AND Process Name:trufflehog.exe
```
