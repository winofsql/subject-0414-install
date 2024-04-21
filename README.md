# subject-220414-install

- ### Google Chrome の設定

  - ### chrome-policy.reg
    ```
    Windows Registry Editor Version 5.00

    [HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome]
    "ShowHomeButton"=dword:00000001
    "AutofillAddressEnabled"=dword:00000000
    "HomepageLocation"="https://www.google.com/"
    "BrowserThemeColor"="#FFFFFF"
    "PromptForDownloadLocation"=dword:00000001
    "AutofillCreditCardEnabled"=dword:00000000
    "ShowAppsShortcutInBookmarkBar"=dword:00000000
    "HomepageIsNewTabPage"=dword:00000000
    "PasswordManagerEnabled"=dword:00000000
    "TaskManagerEndProcessEnabled"=dword:00000001
    "TranslateEnabled"=dword:00000001
    "BrowserAddPersonEnabled"=dword:00000000
    "NTPCustomBackgroundEnabled"=dword:00000000
    
    [HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome\CookiesSessionOnlyForUrls]
    "1"="[*.]google.com"
    "2"="github.com"
    "3"="replit.com"
    "4"="[*.]lolipop.jp"
    "5"="paiza.jp"
    "6"="[*.]zoom.us"
    "7"="twitter.com"
    "8"="chat.openai.com"
    "9"="claude.ai"
    ```
 
  - ブラウザを終了時にログアウトさせるサービスのドメイン
    ```
    [HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome\CookiesSessionOnlyForUrls]
    "1"="[*.]google.com"
    "2"="github.com"
    "3"="replit.com"
    "4"="[*.]lolipop.jp"
    "5"="paiza.jp"
    "6"="[*.]zoom.us"
    "7"="twitter.com"
    "8"="chat.openai.com"
    "9"="claude.ai"
    ```
  - ホームボタンの URL を設定
    ```
    [HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome]
    "HomepageLocation"="https://www.google.com/"
    ```
