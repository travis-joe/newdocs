# Prevent Duplicate Tracking Records When Processing Webhooks

This feature controls what happens when a webhook is received by Deadline Funnel.

You can find this in your Deadline Funnel campaign &gt;&gt; Settings &gt;&gt; Advanced:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b1981a50428632c466aa991/file-uwgHWORSVI.png)

## Possible scenarios:

1

```text
 When this option is **disabled** (default setting) and a tracking lifetime length is set, Deadline Funnel **will create** a new tracking record whenever an incoming webhook is received. 
```

2

```text
 When this option is **disabled** and tracking lifetime is set to 0, Deadline Funnel **will create** a new tracking record when a webhook is received for an email address that **is not** currently being tracked. 
```

3

```text
 When this option is **enabled**  and tracking lifetime is set to 0, Deadline Funnel **will not** create a new tracking record when a webhook is received for an email address that is currently being tracked. 
```

4

```text
 When this option is **enabled** and tracking lifetime is set to a number of days (i.e., 10 days), Deadline Funnel **will create** a new tracking record when an incoming webhook is received for an email that **is not** currently being tracked. 
```

5

```text
 When this option is **enabled** , and tracking lifetime is set to a number of days (i.e., 10 days), Deadline Funnel **will not** create a new tracking record when an incoming webhook is received for an email that **is currently being tracked** when the tracking was created less than 10 days ago. 
```

6

```text
 When this option is **enabled** , and tracking lifetime is set to a number of days (i.e., 10 days), Deadline Funnel **will create** a new tracking record when an incoming webhook is received for an email that is currently being tracked if the tracking was created more than 10 days ago. 
```

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

