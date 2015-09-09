---
	title: Accordion Select
	slug:
---
**It used in listing contents on toggle**

## Demo	

<button
        data-placement="bottom"
        data-animation="am-flip-x"
        id="purchasingOrganization"
        ng-if="categories.length > 0 && allSubcategories.length > 0 && contractTypes.length > 0 && programTypes.length > 0 && availableTo.length > 0 && allSolutions.length > 0"
        model="accordianSelects.agency"
        data-collection="availableTo"
        display-text-field="name"
        value-field=""
        data-target="moreSearch"
        data-target-field="availableTo"
        data-change="changeFilter"
        data-dont-expand-initially="true"
        placeholder="My Agency"
        is-parent-on-empty="fkOptionParentId"
        help="agency"
        help-data="help"
        data-filter-counts="filterCountUpdater.filterCounts.availableTo"
        ag-accordion-select
      ></button>


## HTML

```
 <button
        data-placement="bottom"
        data-animation="am-flip-x"
        id="purchasingOrganization"
        ng-if="categories.length > 0 && allSubcategories.length > 0 && contractTypes.length > 0 && programTypes.length > 0 && availableTo.length > 0 && allSolutions.length > 0"
        model="accordianSelects.agency"
        data-collection="availableTo"
        display-text-field="name"
        value-field=""
        data-target="moreSearch"
        data-target-field="availableTo"
        data-change="changeFilter"
        data-dont-expand-initially="true"
        placeholder="My Agency"
        is-parent-on-empty="fkOptionParentId"
        help="agency"
        help-data="help"
        data-filter-counts="filterCountUpdater.filterCounts.availableTo"
        ag-accordion-select
      ></button>
 ```
## OPTIONS

| Options                  | Type         	   | Default/Values      |   Description              |
| ------------------------ | ----------------- | ------------------- | -------------------------- |      
| target                   |                   |                     |                            |
| targetField              |                   |                     |                            |
| multiple                 |                   |                     |                            |
| placeholder              |                   |                     |                            |
| displayTextField         |                   |                     |                            |
| valueField               |                   |                     |                            |
| collection               |                   |                     |                            |
| change                   |                   |                     |                            |
| isParentOnEmpty          |                   |                     |                            |
| help                     |                   |                     |                            | 
| helpData                 |                   |                     |                            |
| orderBy                  |                   |                     |                            |
| filterCounts             |                   |                     |                            |
| filterCountKey           |                   |                     |                            | 
| model                    |                   |                     |                            |
| expanded                 |                   |                     |                            |
| dontExpandInitially      |                   |                     |                            | 
