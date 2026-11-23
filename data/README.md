# Menu data

Keep the file(s) you use and delete the rest. If you bring your own data,
describe them here the same way: source, license, what one row is, column
meanings, units, and how missing values are coded. `NA` marks a missing value
in every file below. All of these data are CC0 (public domain).

## lizards.csv (hurricane lizards)
164 rows; one row is one Anolis scriptus lizard.
- ID: lizard number
- Hurricane: Before or After (surveyed four days before Hurricane Irma, and
  six weeks later after Irma and Maria)
- Origin: island, Pine Cay or Water Cay
- Sex: Male or Female
- SVL: snout-vent (body) length, mm
- Femur, Tibia, Metatarsal, LongestToe: hind-limb lengths, mm
- Humerus, Radius, Metacarpal, LongestFinger: fore-limb lengths, mm
- FingerCount, ToeCount: number of lamellae (scales) on the toepads
- FingerArea1-3, ToeArea1-3, MeanFingerArea, MeanToeArea, SumFingers, SumToes:
  toepad areas, mm^2
- MaxFingerForce: clinging force, newtons

Source: Donihue et al. (2018), data on Dryad (Donihue et al. 2019).
BibTeX keys: donihue2018, donihue2019data.

## finch_beaks_1975.csv and finch_beaks_2012.csv (Darwin's finches)
403 and 249 rows; one row is one bird measured on Daphne Major in that year.
- band: leg-band number
- species: fortis (medium ground finch) or scandens (cactus finch);
  one 2012 bird is "unknown"
- beak length and beak depth, mm. The 1975 file calls these
  "Beak length, mm" and "Beak depth, mm"; the 2012 file calls them
  blength and bdepth.

Source: Grant and Grant (2014), data on Dryad (Grant and Grant 2013).
BibTeX keys: grant2014, grant2013data, grant2006.

## bird_collisions.csv and mp_light.csv (birds and city lights)
bird_collisions.csv: 69,695 rows; one row is one bird found after hitting a
building in Chicago, 1978-2016.
- genus, species, family: the bird's taxonomy
- date: date found
- locality: MP = McCormick Place; CHI = elsewhere in downtown Chicago
- flight_call: Yes, No, or Rare; whether the species calls in flight at night
- habitat, stratum: habitat and foraging layer of the species

mp_light.csv: 3,067 rows; one row is one night at McCormick Place, 2000-2018.
- date
- light_score: how many of the building's window bays were lit (3 to 17;
  higher means more light)

Source: Winger et al. (2019), data on Dryad (Winger et al. 2019b), as cleaned
for TidyTuesday on 2019-04-30. BibTeX keys: winger2019, winger2019data.

## pie_crab.csv (fiddler crabs)
392 rows; one row is one male Atlantic marsh fiddler crab (Minuca pugnax),
collected in summer 2016 at 13 salt marshes from Florida to Massachusetts.
- date: collection date
- latitude: latitude of the marsh, degrees
- site, name: marsh code and full name
- size: carapace width, mm
- air_temp, water_temp: mean annual air and water temperature at the marsh, C
- air_temp_sd, water_temp_sd: their standard deviations, C

Source: Johnson (2019), from the lterdatasampler R package; paper Johnson et
al. (2019). BibTeX keys: johnson2019data, johnson2019, lterdatasampler.

## hbr_maples.csv (sugar maples and calcium)
359 rows; one row is one sugar maple seedling at the Hubbard Brook
Experimental Forest, measured in August 2003 or June 2004.
- year
- watershed: W1 (calcium added in 1999) or Reference (untreated)
- elevation: Low or Mid
- transect: transect within the watershed; sample: seedling within transect
- stem_length: seedling height, mm
- leaf1area, leaf2area, corrected_leaf_area: leaf areas, cm^2
- leaf_dry_mass, stem_dry_mass: dry masses, g

Source: Juice and Fahey (2019), from the lterdatasampler R package; paper
Juice et al. (2006). BibTeX keys: juice2019data, juice2006, lterdatasampler.

## ntl_icecover.csv and ntl_airtemp.csv (lake ice)
ntl_icecover.csv: 334 rows; one row is one lake in one winter, 1851-2019.
- lakeid: Lake Mendota or Lake Monona
- ice_on, ice_off: freeze and thaw dates
- ice_duration: days of ice cover (3 winters are missing)
- year: the year the winter started

ntl_airtemp.csv: 55,151 rows; one row is one day in Madison, Wisconsin,
1869-2019.
- sampledate, year
- ave_air_temp_adjusted: daily mean air temperature, C (adjusted for biases)

Sources: Magnuson et al. (2021) and Anderson and Robertson (2020), from the
lterdatasampler R package; paper Magnuson et al. (2000).
BibTeX keys: magnuson2021data, anderson2020data, magnuson2000, lterdatasampler.
