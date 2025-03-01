---
title: Connect via SQL Shell
summary: Learn how to connect to your TiDB cluster via SQL Shell.
---

# Connect via SQL Shell

In TiDB Cloud SQL Shell, you can try TiDB SQL, test out TiDB's compatibility with MySQL quickly, and administer database user privileges.

> **Note:**
>
> You cannot connect to [Serverless Tier clusters](/tidb-cloud/select-cluster-tier.md#serverless-tier-beta) using SQL Shell. To connect to your Serverless Tier cluster, see [Connect to Serverless Tier clusters](/tidb-cloud/connect-to-tidb-cluster.md#serverless-tier).

To connect to your TiDB cluster using SQL shell, perform the following steps:

1. Log in to the [TiDB Cloud console](https://tidbcloud.com/) and navigate to the [**Clusters**](https://tidbcloud.com/console/clusters) page of your project.

    > **Tip:**
    >
    > If you have multiple projects, you can switch to the target project in the left navigation pane of the **Clusters** page.

2. Click the name of your target cluster to go to its cluster overview page, and then click **Connect** in the upper-right corner. A connection dialog is displayed.

3. In the dialog, select the **Web SQL Shell** tab, and then click **Open SQL Shell**.

4. On the prompted **Enter password** line, enter the root password of the current cluster. Then your application is connected to the TiDB cluster.