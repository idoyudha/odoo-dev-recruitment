# Odoo tutorials

This repository hosts the code for the bases and solutions of the
[official Odoo tutorials](https://www.odoo.com/documentation/17.0/developer/tutorials.html).

It has 3 branches for each Odoo version: one for the bases, one for
[Discover the JS framework](https://www.odoo.com/documentation/17.0/developer/tutorials/discover_js_framework.html) solutions and one for [Master the Odoo web framework](https://www.odoo.com/documentation/17.0/developer/tutorials/master_odoo_web_framework.html) solutions. For example, `17.0`, `17.0-discover-js-framework-solutions` and `17.0-master-odoo-web-framework-solutions`. 
The first contains the code of the modules that serve as base for the tutorials,
and the others contains the code of each chapter with the complete
solution.

## Getting Started
Run the development server:

1. Build and run the docker container
```bash
docker compose up -d
```
2. Open [http://localhost:5000](http://localhost:8069) with your browser to see the result.
3. Create user and database
4. Install Module "Recruitment"
5. Install Module "MP Recruitment"
6. Install Module "Website"
6. See the result on localhost:8069/jobs or localhost:8069/mpjobs for the simple one