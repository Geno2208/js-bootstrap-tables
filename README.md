# js-bootstrap-tables

Bootstrap tables using vanilla javascript with built-in search, serial no., event-firing, colspan, rowspan, counters and much more...

# Optional Requirements

Bootstrap

# CDN

<script src="https://cdn.jsdelivr.net/gh/TaxHeal-in/js-bootstrap-tables@0.1.9/html.js"></script>
<script src="https://cdn.jsdelivr.net/gh/TaxHeal-in/js-bootstrap-tables@0.1.9/table.js"></script>

# How to use

let headRow = [{ text: `Name` }];

let dataRows = {
checkboxId,
className,
data: [
{text: `Pankaj`},
{text: `Ram`},
{text: `Tarun`}
],
id
};

let newDynamicTable = new DynamicTable({
divId: `tableDiv`,
tableId: `tableData`,
headRow,
dataRows,
head2Row,
footRow,
functionArray,
addFilter: true,
addLimit: true,
addCheckboxes: true,
checkboxClass
});

newDynamicTable.createTable();

# Properties

additionalClass

align

className

colspan

filterText

id

placeholder

rowspan

text

type
