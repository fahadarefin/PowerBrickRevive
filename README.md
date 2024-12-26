# **Retro Brick Charger**

<img src="https://github.com/fahadarefin/PowerBrickRevive/blob/main/RetroBrickCharger.png" alt="Retro Brick Charger" width="500"/>

---

## **⚠️ Safety Notice**

Improper assembly or using low-quality components may cause **fire, electric shock, or device damage**.  
- Ensure all parts are rated for the required voltage and current.  
- Double-check connections and polarity.  
- Test thoroughly with a multimeter before use.  

**Proceed at your own risk.**

---

## **Overview**

The Retro Brick Charger repurposes an old laptop power brick into a modern charger that supports both QC 3.0 and QC 4.0 fast charging protocols. It achieves this by connecting pre-made modules in parallel, enabling compatibility with multiple protocols through a single power source.  

This environmentally friendly project is easy to build, requiring minimal tools and no custom circuit boards.

---

## **Features**
- Simultaneous support for older and newer device charging protocols.  
- DIY-friendly with pre-made modules and standard connectors.  
- Environmentally conscious by reusing old electronics.  
- Includes a 3D-printed enclosure for safety and aesthetics.  

---

## **Components Needed**
1. QC 3.0 Fast charge module.  
2. QC 4.0 Fast charge module.  
3. Female 5.5 mm barrel jack.  
4. Male 5.5 mm barrel jack.  
5. Old laptop power brick (65W).  
6. Connecting wire (rated for 5A).  
7. 3D-printed enclosure (files included in the repository).  
8. Heat-shrink tubing or electrical tape (for insulation).  
9. Glue gun.  
10. Super glue.  
11. Soldering iron and solder (optional but recommended for secure connections).  

---

## **Instructions**

### **1. Preparation**
- Gather all components.  
- Identify the positive (V+) and negative (GND) terminals on the old laptop power brick wires.  

### **2. Connecting the Modules**
- Securely connect the **positive wire from the female barrel jack** to the **input positive terminal (VIN+)** on both QC 3.0 and QC 4.0 modules.  
- Connect the **negative wire from the female barrel jack** to the **input negative terminal (VIN−)** on both QC 3.0 and QC 4.0 modules.  
- Ensure both modules are connected in parallel. This means their inputs share the same positive and negative connections.  
- Double-check the polarity to avoid damage to connected devices.  

### **3. Preparing the Male Barrel Jack**
- Cut the old jack connector from the laptop charger.  
- Strip the wires and identify the positive and negative connections (use a multimeter if needed).  
- Connect the male connector to the output wires from the charger, matching polarity.  

### **4. 3D-Printed Enclosure**
- Print the provided 3D enclosure files.  
- Adjust scaling if needed to account for shrinkage during printing.  
- Place the modules, female barrel jack connectors, and wiring into the enclosure.  
- Use a glue gun to secure the modules in place.  
- Use super glue to properly secure the female barrel jack at the top of the enclosure.  
- Secure all components inside and close the enclosure. *(Optional: You can shut it using super glue.)*

### **5. Testing**
- Use a multimeter to verify voltage levels at the female barrel jack output.  
- Connect a device supporting QC 3.0 or QC 4.0 to test the charger functionality.  

---

## **Notes**
- Module dimensions may vary between batches, so some adjustment might be needed in the 3D enclosure.  
- Ensure proper insulation for all connections to prevent short circuits.  

---

## **Resources**
- [QC 3 module](https://www.electroschematics.com/quick-charge-primer/)  
- [QC 4 module](https://www.dunia.com.bd/product/60w-6-35v-dc-to-usb-type-c-pd-3-0-qc4-type-a-qc3-0-dc-fast-charge-12v-24v-step-down-power-module-usb-type-c-mobile-phone-quick-charge-adapter/)  
- [3D Models](https://github.com/fahadarefin/PowerBrickRevive/tree/main/3dPrintFiles)

---

## **License**
This project is open-source and distributed under the MIT License. Contributions and feedback are welcome!
