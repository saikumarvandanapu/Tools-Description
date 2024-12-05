# Tools Expertise

## 1. Tanner (S-Edit and L-Edit)
### Description:
- **Schematic Creation**: Designed logic gates and simple circuits like:
  - Half Adder, Full Adder
  - Multiplexer, Oscillator, D-Latch, etc.
- **Analysis Performed**:
  - Transient Analysis
  - Parametric Analysis
  - DC Analysis
  - Power Analysis
  - Temperature Analysis
- **Other Tasks**:
  - Generated transistor netlists.
  - Exported schematics to L-Edit.

## 2. Primetime
### Description:
- Familiarity with the **Prime Time Flow**.
- Writing and validating constraints.
- Generating and analyzing timing reports.
- Constraining designs with multiple clocks.
- Applying additional timing constraints for optimization.

## 3. Fusion Compiler
### Description:
- **Design Setup**:
  - Created a design library and imported NDM, technology files, parasitic models, and RTL.
  - Loaded the UPF file into the tool.
- **Timing Constraints**:
  - Wrote MCMM timing constraints and loaded them into the tool.
- **Synthesis and Optimization**:
  - Synthesized and optimized designs.
  - Generated Netlist, SDC, and DEF files.
  - Resynthesized designs for better QoR.
- **Floorplanning**:
  - Created floorplans of various shapes (Square, Rectangular, L, U, T).
  - Shaped blocks, placed pins, I/Os, and macros.
- **Power Planning**:
  - Designed power rings, straps, rails, and PBNS.
- **Clock Tree Synthesis (CTS)**:
  - Set up CTS, identified sink and ignore pins.
  - Wrote clock routing rules (Spacing, Shielding, Metal Width Increasing).
  - Declared logical DRCs (max_tran, max_cap, max_fanout).
  - Ran Classic and CCD CTS for skew optimization.
  - Checked timing reports and minimized hold violations.
- **Routing and Signoff**:
  - Performed global and detailed routing, checked DRCs.
  - Fixed opens, shorts, and floating sets during routing.
  - Ran signoff checks using Star-RC to extract RC.
  - Exported final files: Netlist, GDS II, SDC, SPEF, DEF.
- **Timing Analysis**:
  - Used Prime Time for timing analysis.
  - Fixed timing violations by cell sizing, buffer insertion/deletion, cell swapping, and improving nets.
  - Generated ECO reports.

## 4. Calibre
### Description:
- **Physical Verification**:
  - Performed Design Rule Checking (DRC) and Layout Versus Schematic (LVS) checks.
  - Ensured layout met manufacturing and electrical integrity standards.
