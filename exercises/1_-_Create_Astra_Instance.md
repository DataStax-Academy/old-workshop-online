# Exercice 1 - Create Astra instance


Access to the `ASTRA` service on url [https://astra.datastax.com](https://astra.datastax.com/)

### Register and Login

Use your credentials to log in to ASTRA. Fill out the Log In dialog with your Constellation credentials, and click the Log In button - or register if you are one of the few people left on the earth without a Constellation account.

<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/01.png" height="300" />

<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/02.png" height="300" />


### Fill the Form


- **Set the Compute Size**: For the work we are doing please use `Free tier`. You instance will be there forever, free of charge

- **Select the region**: This is the region where your database will reside physically (choose one close to you or your users). For people in EMEA please use `europe-west-1` idea here is to reduce latency.

- **Fill in the database name** - `killrvideocluster.` While Astra allows you to fill in these fields with values of your own choosing, please follow our reccomendations to make the rest of the exercises easier to follow. If you don't, you are on your own! :)

- **Fill in the keyspace name** - `killrvideo`. It's really important that you use the name killrvideo (with no 'e' in "killr") here in order for all the exercises to work well. We realize you want to be creative, but please just roll with this one today.

- **Fill in the Database User name** - `KVUser`. Note the user name is case-sensitive. Please use the case we suggest here.

- **Fill in the password** - `KVPassword`. Fill in both the password and the confirmation fields. Note that the password is also case-sensitive. Please use the case we suggest here.

- **Launch the database**. Review all the fields to make sure they are as shown, and click the Launch Database button.


<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/03.png" height="400" />


View your database. It may take 2-3 minutes for your database to spin up. You
will receive an email at that point. But, go ahead and continue with the rest of the exercise now.

 Let’s review the database you have configured. In the box on the top-left side of the window, you can see the database and keyspace name metadata. The box on the top-right describes the size and location of your database. The lower-left box shows your estimated cost. Once Apollo initializes the database completely, the lower-right box will have connection details.


