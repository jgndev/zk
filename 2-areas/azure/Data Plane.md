
## Overview

The Data Plane enables interaction with the capabilities of resources after they are created. It focuses on the operational or runtime activities of those resources such as reading and writing, or querying data.

## Characteristics

- Operations are specific to the resource instance and its functionality.
- Governance policies applied at the [[Control Plane]] level may not restrict the Data Plane operations. Example a log preventing deletion of a database doesn't stop data queries.
- Some Data Plane operations can be governed using [[Azure Policy]] in preview modes.