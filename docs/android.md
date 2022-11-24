---
icon: fontawesome/brands/android
---

# :fontawesome-brands-android: Android

## :material-download: Installation

1. Download [V2rayNG](https://play.google.com/store/apps/details?id=com.v2ray.ang) from the Google Play store.

## :material-tools: Configuration
**1.** Copy the below URI to clipboard for the respective proxy service you are configuring:
   
!!! Clipboard
    Select icon on right hand side of text to copy to clipboard
    === "Free Iran"
        ```
        vmess://ew0KICAidiI6ICIyIiwNCiAgInBzIjogIkZyZWUgSXJhbiIsDQogICJhZGQiOiAianNzYW0uZmluLXRlY2guY29tIiwNCiAgInBvcnQiOiAiNDQzIiwNCiAgImlkIjogIjExMzAzZGJlLTBmMDktNGE0Yy1hM2ZmLTdkMTlhMDkyMzhiZCIsDQogICJhaWQiOiAiMCIsDQogICJzY3kiOiAiYXV0byIsDQogICJuZXQiOiAid3MiLA0KICAidHlwZSI6ICJub25lIiwNCiAgImhvc3QiOiAianNzYW0uZmluLXRlY2guY29tIiwNCiAgInBhdGgiOiAiL2NvbnRyb2wiLA0KICAidGxzIjogInRscyIsDQogICJzbmkiOiAianNzYW0uZmluLXRlY2guY29tIiwNCiAgImFscG4iOiAiIg0KfQ==
        ```

    === "Power Vmess"
        ```
        vmess://eyJhZGQiOiJiYWJvLjEzMzcuY3giLCJhaWQiOiIwIiwiYWxwbiI6IiIsImhvc3QiOiJiYWJvLjEzMzcuY3giLCJpZCI6ImVjNjFkNzQxLWQ5NWQtNGM2Ni1iMzU2LTBlZDg5NzgzMTllOSIsIm5ldCI6IndzIiwicGF0aCI6Ii9jb250cm9sLyIsInBvcnQiOiI0NDMiLCJwcyI6IlBvd2VyLVZNRVNTIiwic2N5IjoiYXV0byIsInNuaSI6ImJhYm8uMTMzNy5jeCIsInRscyI6InRscyIsInR5cGUiOiIiLCJ2IjoiMiJ9
        ```

**2.** Run the ***V2rayNG*** app

**3.** On the ***Configuration*** screen, click the ***+*** icon to add a server

**4.** Select ***Import config from clipboard***

<figure markdown>
![](images/android/v2rayng-import.png){:style="height:50%;width:50%" loading=lazy}
</figure>

??? Success

    Successful import confirmation should be displayed

    <figure markdown>
    ![](images/android/v2rayng-imported.png){:loading=lazy style="height:50%;width:50%;"}
    </figure>

**5.** Click on the connect button to connect the VPN

<figure markdown>
![](images/android/v2rayng-con.png){:loading=lazy style="height:50%;width:50%;"}
</figure>

**6.** For the first time only, approve the first use connection request

<figure markdown>
![](images/android/v2rayng-req.png){:loading=lazy style="height:50%;width:50%;"}
</figure>

**7.** Enjoy the internet!

??? success ":material-dns: Test Connection"

    To check if the proxy is properly configured and connected, you can test your connection below.

    !!! Warning
        Ad Blockers may need to be disabled for this website in order for the test to run and not generate a blank page.

    <figure markdown>
    [Test Connection](../check/){ .md-button target=_blank}
    </figure>


## :material-tools: Disconnection

To disconnect from the service, open ***V2rayNG*** and from the main screen, click on the connect/disconnect icon to disconnect:

<figure markdown>
![](images/android/v2rayng-dc.png){:loading=lazy style="height:50%;width:50%;"}
</figure>
