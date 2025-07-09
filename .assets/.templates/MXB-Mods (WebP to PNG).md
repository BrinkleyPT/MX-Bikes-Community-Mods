## PowerShell

>1..16 | ForEach-Object {
  $url = "https://cdn.mxb-mods.com/wp-content/uploads/2024/08/track-preview-$_.png"
  Invoke-WebRequest -Uri $url -OutFile "track-preview-$_.png"
}
