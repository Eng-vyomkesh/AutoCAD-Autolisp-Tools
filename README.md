# AutoCAD AutoLISP Tools & Routines

Collection of custom AutoLISP scripts designed to automate drafting workflows in AutoCAD and AutoCAD MEP.

---

## 📏 1. Total Pipe & Line Length Calculator (`totallength.lsp`)

### Description
A custom LISP routine (`TL`) that calculates and sums the total length of all selected lines, polylines, and arcs in a drawing. Ideal for MEP piping runs, ducting layouts, and quantity take-offs.

### How to Install and Use in AutoCAD
1. Download `totallength.lsp` from this repository.
2. Open your drawing in **AutoCAD**.
3. Type `APPLOAD` in the command bar and press **Enter**.
4. Select `totallength.lsp` and click **Load**.
5. Type `TL` in the command line and press **Enter**.
6. Select the lines/pipes you wish to measure and press **Enter**.
