# HWM095 Manual

 B&R PLC 4-Corner Welding Machine
 Table movements are performed by a servo motor instead of a cylinder.  
 There are burr guide cylinders at top and bottom.

## Manual Mode Page
![HWM095](_media/ManuelMode.png)

**Manual Mode Page :** After selecting the profile defined in the profiles, the X and Y dimensions of the profile are entered. If there are no errors and the alarm-reset has been performed, welding operation is started by pressing the start button. 

## Barcode Page
![HWM095](_media/BarcodeDesign.png)

**Barcode Description :** The necessary parameters for barcode design are modified to create the desired output.

## Manufactures Page
![HWM095](_media/Manufacturers.png)

**Manufacturers :** Profile manufacturers are identified on this page. 

## Profiles Page
![HWM095](_media/Profiles.png)

**Profiles :** Profile details, operations, or general operation times are defined on this page. Profile data can be imported or exported using the 'Import' or 'Export' buttons.

## Colours Page
![HWM095](_media/Colours.png)

**Colours :** General colour and gasket information is created and can be modified on this page.

## Machine Settings Page
![HWM095](_media/ProgramSettings.png)

**Program Settings :** This page contains information such as different welding options, language settings, company, machine model, file separation, and barcode XY multipliers.   

## Options Page
![HWM095](_media/Options.png)

**Options :** The CK and conveyor options to be used in cooling, as well as the gasket press, barcode, and colour options, are selected on this page. 

## Measurement Control Page
![HWM095](_media/MeasControl.png )

**Measurement Control Page :** After entering the X and Y dimensions and pressing the 'Start Measure' button, the final axis movements are performed and the measurement is checked after pressing the 'Finish Measure' button. The relevant axis position is calibrated by pressing the 'Calibrate Axis' button. Resistance and blade offset values ​​can be adjusted from this page. 

## Jog Page
![HWM095](_media/Jog.png )

**Jog Page :** After pressing the 'Jog' button on the Jog page, the corresponding axis button is pressed, and the 'Axis-' and 'Axis+' buttons are used to move in the desired direction.

## Axis Operations Page
![HWM095](_media/AxisOperations.png)

**Axis Operations Page :** On the axis operations page, to reset the position of the relevant axis, enter a value and press the 'Calibrate' button. The calibrated value will then appear in the 'Actual Position' section. Press the 'Jog Activate' button on the relevant axis and then use the - and + buttons to perform a jog movement in the desired direction.

## Input Page
![HWM095](_media/Inputs.png)

**Inputs :** Sensor and switch information can be checked from this page.

## Manual Control Page
![HWM095](_media/Outputs.png)

**Outputs :** On this page, the valves are operated manually after pressing the 'Enable' button. To operate the valves automatically, the 'Automatic' button must be activated.  

## Parameters Page
![HWM095](_media/Parameters.png)

- All machine parameters and the necessary buttons for parameter operations are located on this page.
- The parameters are divided into sections.

### Parameters Page Buttons

- **Save Params**: It saves the changes made on the parameters page.
- **Refresh**: It is used to refresh the page when changes are made.
- **Save As Factory Settings**: The current parameters are saved as factory settings.
- **Load Factory Settings**: Factory settings are restored.
- **Backup Config**: The machine's current axis configuration parameters are exported with the .xml extension.
- **Import Params**: Axis configuration parameters are imported for use in the machine.

### Parameters Sections

#### Burr Guide
![HWM095](_media/BurrGuideParams.png)

**Burr Guide :** The parameters for burr guide pistons are detailed in this section. 

#### Axis Parameters
![HWM095](_media/AxisParams.png)

**Axis Parameters :** Axis speeds, braking distances, and min-max. limit positions are included in this section.

#### General
![HWM095](_media/GeneralParams.png)

**General :** General parameters of the machine are in this section.

#### Profile Measurement
![HWM095](_media/MeasControlParams.png)

**Profile Measurement :** The torque and tolerance values ​​required for axis measurements are included in this section.

#### Table Parameters
![HWM095](_media/TableParams.png)

**Table Parameters :** The position parameters for all table axes and the specific torque values ​​they will apply in the scenario are listed on this page.
