[Landing Page](/Readme.md)

<div align="justify">

# Results documentation

The category serves as a comprehensive repository within the metadata catalog for biocatalytic experiments, capturing a diverse array of metrics and parameters crucial for documenting and analyzing the outcomes of experiments. It provides clear instructions and recommendations for accurately recording and documenting results, encompassing specific units and metrics relevant to biocatalytic reactions.
 
<img src="https://github.com/DomMSNR/Strenda-biocatalysis/assets/106530250/9c81ca9b-ef03-4971-b875-b7420e83a94e" width="250">

## Kinetic parameters

Accurate reporting of kinetic parameters is crucial in biocatalysis as they provide key insights into the efficiency and performance of enzymatic reactions. Parameters like K<sub>m</sub>, V<sub>max</sub>, and K<sub>cat</sub>/K<sub>m</sub> not only elucidate the enzyme-substrate interaction but also aid in optimizing reaction conditions for enhanced catalytic activity and product yield.

<details> <Summary>KineticParameters</Summary>

### KineticParameters

These parameters serve as essential benchmarks for understanding enzyme kinetics.

- __michaelis_constant__
  - Type: float
  - Description: The Michaelis-Menten constant (K<sub>m</sub>​) represents the substrate concentration at which an enzyme achieves half of its maximum reaction rate.
 
- __michaelis_constant_unit__
  - Type: string
  - Description: The unit of the Michaelis-Menten constant (K<sub>m</sub>​) is typically expressed as moles per liter (M or mM).
 
- __maximum_reaction_rate__
  - Type: float
  - Description: V<sub>max</sub>, the maximum reaction rate, represents the speed at which an enzyme-catalyzed reaction reaches saturation, indicating the maximum achievable rate of product formation under optimal substrate concentration.

- __maximum_reaction_rate_unit__
  - Type: string
  - Description: The unit of V<sub>max</sub> (Maximum reaction rate) is typically represented as concentration per time, such as moles per liter per second (mol/L/s or mM/s)
 
- __turnover_number__
  - Type: float
  - Description: The turnover number (K<sub>cat</sub>) measures the number of substrate molecules converted to product per active site of an enzyme per unit time when the enzyme is fully saturated with substrate.

- __turnover_number_unit__
  - Type: string
  - Description: The unit of turnover number (K<sub>cat</sub>) is typically expressed as moles of product per mole of enzyme per second or per minute.
 
- __catalytic_efficiency__
  - Type: float
  - Description: Catalytic efficiency (K<sub>cat</sub>/K<sub>m</sub>) is a measure of how effectively an enzyme converts substrate into product, often quantified as the ratio of the turnover number (K<sub>cat</sub>) to the Michaelis constant (K<sub>m</sub>).
 
- __catalytic_efficiency_unit__
  - Type: string
  - Description: The typical units for catalytic efficiency (K<sub>cat</sub>/K<sub>m</sub>) are usually M<sup>-1</sup>s<sup>-1</sup> or s<sup>-1</sup>.
 
- __dissociation_constant__
  - Type: float
  - Description: The dissociation constant (K<sub>d</sub>) is a measure that represents the equilibrium between a complex and its dissociated components.
 
- __dissociation_constant_unit__
  - Type: string
  - Description: The dissociation constant (K<sub>d</sub>) is typically expressed in M (molarity) or its derivatives, such as nM (nanomoles per liter).
 
- __inhibition_type__
  - Type: string
  - Description: Enzyme inhibition encompasses various forms, including competitive, non-competitive, uncompetitive, mixed, and irreversible inhibition. Each type has different effects on the enzyme's function and plays a crucial role in regulating biochemical processes.

- __inhibition_constant__
  - Type: float
  - Description: The inhibition constant (K<sub>i</sub>) is a significant parameter in biocatalysis, describing the affinity of an inhibitor for an enzyme. It indicates how effectively an inhibitor influences enzyme activity. A lower K<sub>i</sub> value suggests a strong binding of the inhibitor to the enzyme.

- __inhibition_constant_unit__
  - Type: string
  - Description: The units for the inhibition constant (K<sub>i</sub>) are commonly expressed in molar concentration (M) or related units.
 
- __hill_coefficient__
  - Type: float
  - Description: The Hill coefficient is a parameter used to describe cooperativity in the binding of molecules to proteins. It is employed in enzyme reactions or oxygen binding to hemoglobin to indicate whether there is positive (cooperative) or negative (anticooperative) binding. A Hill coefficient greater than 1 indicates positive cooperativity, while a value less than 1 indicates negative cooperativity. A value of exactly 1 indicates no cooperativity in the binding.
  

<hr>

- __special_treatment__
  - Type: string
  - Description: If there are any other specific metrics, parameters, characteristics or aspects related to the kinetics that are important to document the results accurately and are not described by the aforementioned metadata, they should be explained here.

</details>


<hr>

## Yield and conversion

The documentation of yield and conversion in biocatalysis is crucial as it provides essential insights into the efficiency of a reaction and the amount of desired product obtained.

<details> <Summary>YieldAndConversion</Summary>

### YieldAndConversion

These metrics are vital for evaluating the success of a process, optimizing reaction conditions, and ensuring the production of high-quality products in biocatalytic applications.

- __yield__
  - Type: posfloat
  - Description: Yield represents the amount of the desired product obtained from a reaction. 
 
- __yield_unit__
  - Type: string
  - Description: The yield is typically expressed in percentages (%), reflecting the ratio of the actual obtained product quantity to the theoretical maximum product quantity that could be obtained under ideal conditions.
 
- __space_time_yield__
  - Type: posfloat
  - Description: Space-time yield in biocatalysis refers to the amount of product obtained per unit volume of the reactor per unit time.
 
- __space_time_yield_unit__
  - Type: string
  - Description: Space-time yield is commonly expressed in g/L/h (grams per liter per hour) or mol/L/h (moles per liter per hour).

- __conversion__
  - Type: float
  - Description: The term "conversion" in biocatalysis refers to the percentage of substrate that undergoes transformation into the desired product during a reaction.
 
- __conversion_unit__
  - Type: string
  - Description: The conversion is commonly expressed as a percentage (%) to indicate the proportion of substrate converted to the desired product during a specific reaction.
 
<hr>

- __special_treatment__
  - Type: string
  - Description: If there are any other specific metrics, parameters, characteristics or aspects related to the conversion or yield that are important to document the results accurately and are not described by the aforementioned attributes, they should be explained here.
  
</details>


<hr>

## Reaction rate

The accurate documentation of the reaction rate in biocatalysis is fundamental as it provides insight into the initial rate of the enzymatic reaction. This parameter aids in understanding the velocity at which the substrate is converted into products, offering vital information for assessing the enzyme's efficiency and the reaction kinetics. Furthermore, monitoring the reaction rate assists in optimizing reaction conditions and evaluating the catalytic performance of the enzyme under specific experimental setups.

<details> <Summary>Reaction rate</Summary>

### ReactionRate

The specification of the reaction rate is crucial as it provides insights into the speed and efficiency of the biocatalytic process. It allows for the characterization of enzyme activity and is fundamental for optimizing reaction conditions and quantifying the reaction speed.

- __initial_reaction_rate__
  - Type: float
  - Description: The initial reaction rate refers to the rate at which the product is formed at the beginning of the enzymatic reaction under specific initial substrate concentrations and reaction conditions.
 
- __initial_reaction_rate_unit__
  - Type: string
  - Description: Typically, the initial reaction rate is expressed as mol/L/min (moles per liter per minute) or µmol/mL/min (micromoles per milliliter per minute).

- __specific_activity__
  - Type: posfloat
  - Description: The specific activity refers to the amount of product formed or substrate consumed per unit of enzyme per unit of time.
 
- __specific_activity_unit__
  - Type: string
  - Description: The specific activity is typically expressed in µmol/min/mg (micromoles per minute per milligram of protein).

<hr>

- __special_treatment__
  - Type: string
  - Description: If there are any other specific metrics, parameters, characteristics or aspects related to the reaction rate that are important to document the results accurately and are not described by the aforementioned attributes, they should be explained here.

</details>


<hr>


## Selectivity and specificity

The inclusion of selectivity and specificity data is crucial in biocatalysis as it offers insights into the precision and efficiency of a catalyst's performance. These parameters determine the catalyst's ability to favorably convert specific substrates into desired products, providing critical information for evaluating the catalyst's effectiveness and suitability for a given reaction.

<details> <Summary>Selectivity and Specificity</Summary>

### SelectivityAndSpecificity

These parameters directly assess a catalyst's precision in converting specific substrates to desired products.

- __enantiomeric_excess__
  - Type: posfloat
  - Description: The enantiomeric excess measures the degree of purity and efficiency in a chiral catalysis process, representing the excess of one enantiomer over the other in a reaction product.
 
- __enantiomeric_excess_unit__
  - Type: string
  - Description: The primary unit used for enantiomeric excess is percent (%).

- __chemoselectivity__
  - Type: string
  - Description: Chemoselectivity refers to the ability of a chemical reaction to target a specific functional group or site within a molecule without affecting other reactive groups present. It highlights the preference of a reaction for one type of chemical bond or functional group over others in a molecule. Chemoselective reactions play a crucial role in organic synthesis, allowing precise modification or transformation of a compound while leaving other parts of the molecule unaffected.
 
- __regioselectivity__
  - Type: string
  - Description: Regioselectivity refers to the preference of a reaction to occur at a specific site within a molecule or compound that has multiple potential reaction sites. It describes the tendency of a reaction to selectively take place at a particular position of the molecule, considering its structural arrangement of atoms or functional groups, rather than at other possible sites.
 
- __stereoselectivity__
  - Type: string
  - Description: Stereoselectivity refers to the preference of a chemical reaction to produce a specific stereoisomer or a particular spatial arrangement of atoms within a molecule. It describes the ability of a reaction to favor the formation of one stereoisomer over others or to create a specific stereochemical outcome. This selectivity is essential in organic synthesis and drug development as it determines the spatial arrangement of molecules and their biological activity.

<hr>

- __special_treatment__
  - Type: string
  - Description: If there are any other specific metrics, parameters, characteristics or aspects related to the selectivity and specificity that are important to document the results accurately and are not described by the aforementioned attributes, they should be explained here.

</details>

<hr>


## Specific substrate metrics

Accurate documentation of specific substrate metrics is crucial in biocatalysis as it enables a detailed understanding of enzyme-substrate interactions, aiding in optimizing reaction conditions.

<details> <Summary>Specific substrate metrics</Summary>

### SpecificSubstrateMetrics

These metrics play a pivotal role in determining the catalytic efficiency and selectivity of the enzymatic reactions, thereby influencing the success and reproducibility of the biocatalytic process.

- __substrate_concentration__
  - Type: posfloat
  - Description: The substrate concentration refers to the amount or concentration of the reactant molecules present in a given volume of the reaction mixture.
 
- __substrate_concentration_unit__
  - Type: string 
  - Description: The typical units for substrate concentration in biocatalysis often involve mol/L (moles per liter) or mmol/L (millimoles per milliliter).

- __product_concentration__
  - Type: posfloat
  - Description: The product concentration refers to the amount of the desired product present in a given volume of a reaction mixture.
 
- __product_concentration_unit__
  - Type: string
  - Description: The typical units for product concentration in biocatalysis are expressed as mol/L (moles per liter) or mmol/mL (millimoles per milliliter). 

<hr>

- __special_treatment__
  - Type: string
  - Description: If there are any other specific metrics, parameters, characteristics or aspects related to the selectivity and specificity that are important to document the results accurately and are not described by the aforementioned attributes, they should be explained here.

</details>

<hr>


## Enzyme performance

The indication of enzyme performance is crucial in assessing the effectiveness and reliability of enzymatic reactions. 

<details> <Summary>Enzyme performance</Summary>

### Enzyme performance

Describing enzyme performance allows researchers to understand the enzyme's capability, its longevity under specific conditions, and its overall efficiency in catalyzing reactions, providing valuable insights for optimization and application in various biocatalytic processes.

- __temperature_optimum__
  - Type: float
  - Description: The temperature optimum denotes the specific temperature at which an enzyme demonstrates its highest level of activity or efficiency in a reaction.
 
- __temperature_optimum_unit__
  - Type: string 
  - Description: The temperature optimum is typically measured in °C, K or °F.

- __pH_optimum__
  - Type: posfloat
  - Description: The pH optimum refers to the specific pH level at which an enzyme exhibits its maximum activity or efficiency in a reaction.
 
- __enzyme_stability__
  - Type: string
  - Description: The stability of enzymes is often characterized by various parameters such as the enzyme's half-life under specific conditions, the decline in activity over time, or the preservation of catalytic activity under different environmental conditions. 

<hr>

- __special_treatment__
  - Type: string
  - Description: If there are any other specific metrics, parameters, characteristics or aspects related to the enzyme performance that are important to document the results accurately and are not described by the aforementioned attributes, they should be explained here.

</details>


<hr>


## Thermodynamic parameters

The indication of thermodynamic parameters in biocatalysis is crucial for deepening the understanding of reaction kinetics and efficiency. These parameters offer insights into energy changes occurring during the reaction and assist in estimating reaction heat, entropy, and free energy. Understanding the thermodynamic properties of a reaction is essential to determine reaction direction, stability of intermediates, and the level of spontaneity or enforcement of a reaction.

<details> <Summary>Thermodynamic parameters</Summary>

### Thermodynamic parameters

Understanding the energy dynamics and spontaneity of reactions through thermodynamic parameters is essential for efficient biocatalysis.

- __gibbs_free_energy_change__
  - Type: string
  - Description: The Gibbs free energy (__G__) represents the portion of energy capable of performing work in a reaction under constant temperature and pressure, providing insights into the spontaneity of the reaction. While the absolute value of the free energy cannot be measured directly, the change in free energy (Δ**G**) throughout the reaction, known as free reaction enthalpy, is measurable. As indicated by the Gibbs-Helmholtz equation, it depends on changes in enthalpy (heat content) and entropy (system disorder) during the reaction. <br>
Δ**G** < 0: The reaction proceeds spontaneously; it is __exergonic__. <br>
Δ**G** = 0: The system is at equilibrium; no work is performed. <br>
Δ**G** > 0: The reaction does not proceed spontaneously; it is __endergonic__. A supply of free energy is required to drive the reaction.
 
- __enthalpy_change__
  - Type: string 
  - Description: The enthalpy (**H**) represents the heat content within a system, expressing the quantity and nature of chemical bonds. This thermodynamic property cannot be measured independently. However, measurable is the change in enthalpy (Δ**H**), which refers to the amount of heat absorbed or released during a chemical reaction (under constant pressure), also known as the reaction enthalpy. <br>
Δ**H** > 0: Heat energy is supplied; the reaction is endothermic. <br>
Δ**H** < 0: Heat energy is released; the reaction is exothermic.

- __entropy_change__
  - Type: string
  - Description: The entropy (**S**) is a measure of the degree of disorder in a system or the likelihood of a state. Systems inherently tend towards maximum disorder. Every natural process involves an increase in entropy (disorder). If entropy decreases in one area, it must increase elsewhere correspondingly. The increase in entropy can act as a driving force. <br>
Δ**S** > 0: The disorder of the system increases. <br>
Δ**S** < 0: The disorder of the system decreases.
 
<hr>

- __special_treatment__
  - Type: string
  - Description: If there are any other specific metrics, parameters, characteristics or aspects related to the thermodynamic parameters that are important to document the results accurately and are not described by the aforementioned attributes, they should be explained here.

</details>

<hr>




# blablablabla
The description of the biocatalyst also includes information on its storage conditions prior to use in the reaction. No information is required for fresh production without storage.

<details> <Summary>blablablablabla</Summary>

### blablablabla

- __temperature__
  - Type: float
  - Description: The temperature at which the reactant is stored.

<hr>
 
- __special_treatment__
  - Type: string
  - Description: If there are any other specific characteristics or aspects related to the biocatalyst that are important for reproducibility and are not described by the aforementioned metadata, they should be             explained here.


</details>

<hr>

### Literature

[1] B. Ansorge-Schumacher, M. (2018). Enzymimmobilisierung. In: Jaeger, KE., Liese, A., Syldatk, C. (eds) Einführung in die Enzymtechnologie. Springer Spektrum, Berlin, Heidelberg. https://doi.org/10.1007/978-3-662-57619-9_11


</div>