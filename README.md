# LinkedIn Company Scraper

Interested in using this scraper? Get it here: [LinkedIn Company Scraper](https://apify.com/pratikdani/linkedin-company-profile-scraper). Scrape LinkedIn companies and extract complete information in bulk.

## Features

**Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. You can select the fields you want, allowing for seamless integration with other tools and platforms for further analysis and utilization.

**Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the actor has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

**Ability to Resume Last Failed Runs:** In case of unexpected errors, you can simply go to the actor's last run page and click on the 'Resurrect' button to resume the last scraping progress.

## Integrations

You can use [Make](https://www.make.com/en/register) to integrate the LinkedIn company scraper with any other SaaS platform by designing your own automation flows.

## Sample Output

Here is a sample output of this actor:

```json
{
  "affiliated_pages_data": [],
  "background_cover_image_url": null,
  "company_id": "162479",
  "company_name": "Apple",
  "company_type": "Public Company",
  "description": "We’re a diverse collective of thinkers and doers, continually reimagining what’s possible to help us all do what we love in new ways. And the same innovation that goes into our products also applies to our practices — strengthening our commitment to leave the world better than we found it. This is where your work can make a difference in people’s lives. Including your own.\n\nApple is an equal opportunity employer that is committed to inclusion and diversity. Visit apple.com/careers to learn more.",
  "employees": "171,148",
  "employees_data": [
    {
      "link": "https://www.linkedin.com/in/pdking?trk=org-employees",
      "name": "Paul King",
      "title": "Sr. Data Science Manager at Apple; fmr Computational Neuroscientist, Software Technologist"
    },
    {
      "link": "https://www.linkedin.com/in/instanttim?trk=org-employees",
      "name": "Timothy Martin",
      "title": null
    },
    {
      "link": "https://www.linkedin.com/in/evitiello?trk=org-employees",
      "name": "Eric Vitiello",
      "title": "Software Engineering Manager at Apple"
    },
    {
      "link": "https://www.linkedin.com/in/kevinlynch2?trk=org-employees",
      "name": "Kevin Lynch",
      "title": "VP Technology, Apple"
    }
  ],
  "followers": "17,563,839",
  "founded_year": "1976",
  "headcount": "10,001+ employees",
  "hq_address": {
    "is_hq": true,
    "line_1": "1 Apple Park Way",
    "line_2": "Cupertino, California 95014, US"
  },
  "industry": "Computers and Electronics Manufacturing",
  "location": "Cupertino, California",
  "profile_pic_url": null,
  "similar_pages_data": [
    {
      "industry": "Software Development",
      "link": "https://www.linkedin.com/company/google?trk=similar-pages",
      "location": "Mountain View, CA",
      "name": "Google"
    },
    {
      "industry": "Software Development",
      "link": "https://www.linkedin.com/company/amazon?trk=similar-pages",
      "location": "Seattle, WA",
      "name": "Amazon"
    },
    {
      "industry": "Software Development",
      "link": "https://www.linkedin.com/company/microsoft?trk=similar-pages",
      "location": "Redmond, Washington",
      "name": "Microsoft"
    },
    {
      "industry": "Entertainment Providers",
      "link": "https://www.linkedin.com/company/netflix?trk=similar-pages",
      "location": "Los Gatos, CA",
      "name": "Netflix"
    },
    {
      "industry": "Software Development",
      "link": "https://www.linkedin.com/company/meta?trk=similar-pages",
      "location": "Menlo Park, CA",
      "name": "Meta"
    },
    {
      "industry": "Motor Vehicle Manufacturing",
      "link": "https://www.linkedin.com/company/tesla-motors?trk=similar-pages",
      "location": "Austin, Texas",
      "name": "Tesla"
    },
    {
      "industry": "Musicians",
      "link": "https://se.linkedin.com/company/spotify?trk=similar-pages",
      "location": "Stockholm, Stockholm County",
      "name": "Spotify"
    },
    {
      "industry": "IT Services and IT Consulting",
      "link": "https://www.linkedin.com/company/ibm?trk=similar-pages",
      "location": "Armonk, New York, NY",
      "name": "IBM"
    },
    {
      "industry": "Business Consulting and Services",
      "link": "https://www.linkedin.com/company/deloitte?trk=similar-pages",
      "location": null,
      "name": "Deloitte"
    },
    {
      "industry": "Software Development",
      "link": "https://www.linkedin.com/company/linkedin?trk=similar-pages",
      "location": "Sunnyvale, CA",
      "name": "LinkedIn"
    }
  ],
  "specialities": [
    "Innovative Product Development",
    "World-Class Operations",
    "Retail",
    "Telephone Support"
  ],
  "tagline": null,
  "universal_name_id": "apple",
  "update_data": [],
  "website": "http://www.apple.com/careers"
}
```

## Output Data Documentation

Here is the JSON fields documentation without including the sample values:

- **company_name** (string): The name of the company.
- **affiliated_pages_data** (string): List of affiliated companies.
- **background_cover_image_url** (string): The URL of the company's background cover image.
- **company_id** (string): LinkedIn's internal and immutable ID of this company profile.
- **company_type** (string): The type of company (e.g., Public Company).
- **description** (string): A textual description of the company.
- **employees** (string): The number of employees as indicated on LinkedIn.
- **followers** (string): The number of followers of the company.
- **founded_year** (string): The year the company was founded.
- **headcount** (string): The range of company headcount.
- **hq_address** (string): The company's headquarters address.
- **industry** (string): The industry in which the company operates.
- **location** (string): The location of the company.
- **profile_pic_url** (string): The URL of the company's profile picture.
- **similar_pages_data** (string): List of similar companies.
- **specialities** (string): A list of specialties.
- **tagline** (string): A short, catchy phrase that represents the company's mission or brand.
- **universal_name_id** (string): A unique numerical identifier for the company used on the LinkedIn platform.
- **update_data** (string): List of company updates.
- **website** (string): The company's website.
