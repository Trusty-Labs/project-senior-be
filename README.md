# Senior Backend Engineer Project

The goal of this project is to evaluate your ability to work with large datasets and present them in a usable format for a front end application.

**Summary**
Store the California residential properties data in a postgres database and create a endpoint that allows the searching of properties.  The address search input parameter will be formatted as
```
{
    "primary_line": "185 BAYSIDE VILLAGE PL",
    "city": "SAN FRANCISCO",
    "state": "CA",
    "zip_code": "94107"
}
```

**Requirements**
- Store the properties.csv in S3
- Create service Ingest from S3 and store the attached properties.csv into a AWS Postgres RDS database.
- Optimize table for searching address
- Create lamda endpoint that returns property data based on address input
- Provide curl example to consume endpoint

**Technology Stack**
- Typescript
- AWS RDS - Postgress
- AWS Lambda for endpoint
- AWS S3

**Extra Credit**
- Use GraphQL
- Use Elastic Search
- Simple front end that allows searching of addresses
- Tests
