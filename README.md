# Fire Ecology Traits for Plants

The ***Fire Ecology Traits for Plants*** project is being developed by  [José R. Ferrer-Paris](https://github.com/jrfep) and David Keith in the [Centre for Ecosystem Science](https://github.com/ces-unsw-edu-au), University of New South Wales

Please cite this work as:

> Ferrer-Paris, J. R. and Keith, D. A. (2022) Fire Ecology Traits for Plants: A database for fire research and management. Version 1.00. Centre for Ecosystem Science, University of New South Wales, Sydney, Australia. Retrieved from osf.io/hu96w


This work has been supported by:

- [University of New South Wales, Sydney](https://www.unsw.edu.au/)
- [NSW Bushfire Research Hub](https://www.bushfirehub.org/)
- [NESP Threatened Species Recovery Hub](https://www.nespthreatenedspecies.edu.au/)
- [NSW Department of Planning & Environment](https://www.planning.nsw.gov.au/)

## Components of the project

### Source code for preparing data records

:dart: [This repository](https://github.com/ces-unsw-edu-au/fireveg-db-exports) contains R, Python and SQL code to export data records from the database and upload to data repositories.

The code is documented using Jupyter Notebooks.

This repository is part of the OSF project component:

> Ferrer-Paris, J. R., Keith, D., & Sánchez-Mercado, A. (2024, August 14). Export data records from Fire Ecology Traits for Plants database. Retrieved from [osf.io/h96q2](https://osf.io/h96q2)

***This code is intended for internal project management.*** 🛂 Only users contributing directly to the project have access to the credentials for database connection and write access to our repositories. 

Instructions and documentation are provided for the sake of reproducibility, feel free to use them as inspiration for your project.

### Project overview


This project consists of several linked components:

***🔥 Fire Ecology Traits for Plants: A database for fire research and management*** OSF project [osf.io/hu96w](https://osf.io/hu96w/) with following components:

  - :file_cabinet: **SQL structure of the fireveg database** [osf.io/4csyz](https://osf.io/4csyz)
    - :gear: Source code for defining the structure of the tables in a PostgreSQL database is available in this [GitHub repository](https://github.com/ces-unsw-edu-au/fireveg-db)
  - :briefcase: **Code for populating the fireveg database** [osf.io/rj68t](https://osf.io/znuge)
    - :gear: Source code for populating and managing the database is available in this [GitHub repository](https://github.com/ces-unsw-edu-au/fireveg-db-imports)
  - :computer: **Webapp for browsing the fireveg database** [osf.io/rj68t](https://osf.io/rj68t)
    - :gear: Source code for setting up and running the Flask webapp id available in the [GitHub repository](https://github.com/ces-unsw-edu-au/fireveg-webapp)
    - :computer: Acess to the [Webapp](http://fireecologyplants.net) (Register with a verified email address)
  - :bar_chart: **Data coverage of Fire Ecology Traits for Plants database** [osf.io/h96q2](https://osf.io/h96q2/)
    - :gear: Source code in [GitHub repository](https://github.com/ces-unsw-edu-au/fireveg-db-exports/)
    - :label: A Database snapshot (SQL dump) is available as a Figshare dataset with DOI:[10.6084/m9.figshare.23361002](https://doi.org/10.6084/m9.figshare.23361002)
    - :label: Database exports (summary tables, CSV/XLSX formats) available as Figshare dataset with DOI:[10.6084/m9.figshare.24125088](https://doi.org/10.6084/m9.figshare.24125088)

  - :technologist: **Fire Ecology Traits for Plants: Status of the database** [osf.io/kjevh](https://osf.io/kjevh)
    - :gear: Source code in [BitBucket repository](https://bitbucket.org/fireveg/fireveg-presentations)
    - :speech_balloon: [Presentation slides](https://rpubs.com/jrfep/firevegdb-ESA2023) 


