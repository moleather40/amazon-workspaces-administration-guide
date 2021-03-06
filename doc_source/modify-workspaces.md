# Modify a WorkSpace<a name="modify-workspaces"></a>

You can increase the size of the root and user volumes for a WorkSpace, up to 1000 GB each\. You can expand these volumes whether they are encrypted or unencrypted\. You can request a volume expansion once in a 24\-hour period\.

You can switch a WorkSpace between Value, Standard, Performance, and Power bundles\. When you request a bundle change, Amazon WorkSpaces reboots the WorkSpace using the new bundle\. Amazon WorkSpaces preserves the operating system, applications, data, and storage settings for the WorkSpace\. You can request a larger bundle once in a 24\-hour period or a smaller bundle once in 30 days\.

**To modify the configuration of a WorkSpace**

1. Open the Amazon WorkSpaces console at [https://console\.aws\.amazon\.com/workspaces/](https://console.aws.amazon.com/workspaces/)\.

1. In the navigation pane, choose **WorkSpaces**\.

1. Select the WorkSpace and choose **Actions**, **Modify WorkSpace**\.

1. To increase the size of the root volume or user volume, choose **Modify Volume Sizes** and type the new values\.

1. To change the bundle, choose **Change Compute Type** and select the new bundle type\.

1. Choose **Modify**\.