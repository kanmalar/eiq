# Scenario 1

We are looking for clear and concise content that follows standard
principles and best practices of technical writing.

This assignment should take about 2 to 3 hours in total.

**Exercise 1:**

1. Rewrite the sample below (_Chapter 1: Matching and Searching_),
   so that it complies with best practices in modern technical writing.

1. Provide feedback on the main issues affecting the original sample text,
   from a technical writer’s perspective.

**Exercise 2:**

You find out that the home Internet connection at a friend’s place is open to snooping.

1. How would you explain the issue and the potential consequences to them?
1. What would you recommend they do to mitigate risk?

> Hint:
> 
> - You can structure this assignment as concept and/or task topics.
> - Use a style and tone of voice that is appropriate for technical
> communication.)

# Exercise 1

## Chapter 1: Matching and Searching

Databases can contain lots of data.
If you want to search something that matches existing data records, 
it can become a very difficult task.

For example take into consideration this:

- You are given a list of names, email addresses,
  and companies, and you've got to see if they
  match any existing data records.
   
- There is a database with millions and millions of records, 
  entries, and rows. This data is inside tables so each table 
  holds specific content like contact information including 
  first name, last name, email address, company, etc. etc.
   
- You are charged with the task of looking at each given record
  (could be one, could be 1,000 &mdash; it depends on who asks you),
  and seeing if that record exists somewhere in the database.
   
This is usually when things get tricky because the information
you want to look up is not the same in the database and in your list.
Just for example:

1. The companies in the list and in the database may not be exactly the same.

1. The data in the database is not necessarily normalized, 
   and neither are the given data records.

1. The names in the list that you need to find matches for
   may be nicknames (Mike, Michael, Mick, etc).

1. The names in the database may be names like Mike Portsworth,
   so the nicknames may not even be there for you to find them.
   
The complexity of the matching and searching of the data is directly
proportional to the amount of human involvement in the processing
of said data. In other words, the more people create the data,
the more variations and differences there can be on each data field,
regardless of the fact that they represent the same information details,
and so the more the process relies on human intervention to make the matches,
the longer it takes to get the job done.

The Contact Mapping Tool was created to fill such a gap,
between human-powered "eyeballing" and rules-based
computerized data processing. But even in theory,
such a computerized system can only do so much.
The concession then is to match as much data as possible,
as accurately as possible, then present enough
data to a human user to finish the rest,
reducing the amount of work required by the human analyst,
and so increasing the overall throughput of
each human analyst.

In this way the content mapping tool becomes sort of a pre-processor
that takes care of executing all the grunt work that is so hard for humans to do
like searching, normalizing, sorting, deduplicating, and presenting the data in a way
that makes it easier for humans to analyze.
