# Creating an Email Flow Rule<a name="create-email-rules"></a>

To create an email flow rule, you specify a [rule action](email-flows.md#email-flows-rule-actions) to apply to an email when a specified [pattern](email-flows.md#email-flows-patterns) is matched\. When you create a new email flow rule, it's applied immediately\.

**To create a new email flow rule**

1. Open the Amazon WorkMail console at [https://console\.aws\.amazon\.com/workmail/](https://console.aws.amazon.com/workmail/)\.

1. In the navigation pane, choose **Organization settings**, **Inbound/Outbound rules**\.

1. Choose **Create Rule**\.

1. Enter a name for your rule\.

1. Do one of the following:
   + For inbound email flow rules, enter one or more sender patterns\. 
   + For outbound email flow rules, enter one or more sender patterns and one or more recipient patterns\.

1. Select the action to apply to the email\.

1. Choose **Create Rule**\.

You can test the new email flow rule that you created\. For more information, see [Testing an Email Flow Rule](test-email-flow-rule.md)\.