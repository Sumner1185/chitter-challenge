
Chitter Challenge:
-------
We are going to write a small Twitter clone that will allow the users to post messages to a public stream.

Features:
-------

```
STRAIGHT UP

As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a Maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

HARDER

As a Maker
So that only I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

ADVANCED

As a Maker
So that I can stay constantly tapped in to the shouty box of Chitter
I want to receive an email if I am tagged in a Peep
```

## Initial Domain Model Diagrams:

### Add Peep:
<p align="center">
<img src=/images/add_peep_sequence.svg width=50%>
</p><br><br>

### View Peeps:
<p align="center">
<img src=/images/view_peeps_sequence.svg width=50%>
</p><br><br>

## Instructions For Database Setup:

1. Connect to `psql`
2. Create the database using the `psql` command `CREATE DATABASE chitter;`
3. Connect to the database using the `pqsl` command `\c chitter;`
4. Run the query we have saved in the file `01_create_peep_manager_table.sql`
5. Run the query we have saved in the file `02_add_time_to_peeps.sql`

## Test Database Setup:

1. Connect to `psql`
2. Create the database using the `psql` command `CREATE DATABASE chitter_test;`
3. Connect to the database using the `pqsl` command `\c chitter_test;`
4. Run the query we have saved in the file `01_create_peep_manager_table.sql`
5. Run the query we have saved in the file `02_add_time_to_peeps.sql`
