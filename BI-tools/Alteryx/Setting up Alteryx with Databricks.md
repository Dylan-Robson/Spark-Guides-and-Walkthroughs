<p align="center">
  <a href="" rel="noopener">
 <img width=400px height=400px src="https://i.imgur.com/MoG8Fr2.png" alt="Databricks Web Interface"></a>
</p>

<h3 align="center">Connecting Alteryx to Databricks</h3>

---

<p align="center"> This documentation provides a detailed process on how to properly setup a connection to Databricks
	with Alteryx Designer to utilize Apache Spark's framework.
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](getting_started)
- [Connecting Alteryx to Databricks](#connecting_alteryx_to_databricks)
- [Spark Coding in Alteryx](#spark_coding_in_alteryx)

## 🔎 About <a name = "about"></a>
This guide will provide the step by step process for setting up Alteryx Designer to connect to your companies Databricks environment.
Once connected you will learn how to utilize Apache Spark for querying the connected Databricks Cluster.

## 🏁 Getting Started <a name = "getting_started"></a>
To get started we will need to head over to the Databricks UI and create a personal access token to allow a Alteryx to connect using the
the Databricks API.

### Prerequisites
The following prerequisites are needed for connecting Alteryx to Databricks

- [Access to Databricks](#access_to_databricks)
- [Personal Access Token](#personal_access_token)
- [Cluster Information](#cluster_information)

### Access to Databricks <a name = 'access_to_databricks'></a>
The main prerequisite that is needed to connect and utilize Databricks within Alteryx Designer is the ability to access the Databricks UI.
If you do not have access to the Databrick Environment you're trying to use within Alteryx please contanct the Admin and workthrough
gaining access and return to this guide when setup.

If you do have access and can connect to the Databricks Web Interface you should now and when connected your browser should look similar
to this.

<p align="center">
  <a href="" rel="noopener">
 <img width=400px height=400px src="https://i.imgur.com/MoG8Fr2.png" alt="Databricks Web Interface"></a>
</p>

