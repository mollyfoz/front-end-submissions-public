## Project Name:

#### Check In: 1

#### Project Pitch
Approximately 6.5 million animals enter shelters every year in the US. 1.5 million of those animals are euthanized. 5% of those animals are senior or adult animals. Shelters often stop actively trying to home older animals. The short term objective of this project is to provide a useful search tool that showcases senior and adult dogs and cats. The long term objective of this project is to have this project featured on other larger adoption websites to catch the interest of adopters that may be thinking of adopting an older companion animal. 

### Deliverables

#### Stack:
React/Redux/Router
Testing with Jest/Enzyme/FetchMock

#### APIs:
- PetFinder & Google Maps

#### Wireframes
[Home Page](https://user-images.githubusercontent.com/23444655/30126796-5f50edd2-92fa-11e7-8a22-8c5d616496db.png)
[Category Page](https://user-images.githubusercontent.com/23444655/30126798-62e10572-92fa-11e7-9dd8-c4100c75cffd.png)
Note home page and category pages will be relatively similar, but will filter by cat/dog/all pets. Category page will scroll.
[Single Pet View](https://user-images.githubusercontent.com/23444655/30126807-66d8edf2-92fa-11e7-9857-27f0ef7b989f.png)
[Color Palette](https://color.adobe.com/Color-Theme-2-color-theme-9953340/edit/?copy=true)

#### Waffle & Github
[GitHub: FureverFriends](https://github.com/mollyfoz/FureverFriends)
[Waffle](https://waffle.io/mollyfoz/FureverFriends)

#### Order Of Attack
1. Build out file structure & component skeletons. Add some very basic styles.
2. Set up api fetch. Data is, by default, XML. Will need to properly configure to JSON and clean based on targets.
3. Show data on the appropriate components (route appropriately) and make sure that design is responsive. 
4. Create a search component that allows search by location. Will return local shelters.
5. Home page will have random feature of 4-6 pets in need of adoption.
6. Final data display components should include dogs, cats, and all available animals within age range.
7. Ability to favorite select animals and see the corresponding data on dedicated page.
* Try to actually TDD

#### MVP

- user can filter by location 
- user can 'dogear' a dog 
- user can see shelters on map 
- dog show page. 

All items listed under Order of Attack.

#### Nice To Haves
Ability to sign in and sign out. Will need a backend for this feature.
Local storage.
External links to the shelter websites where the animals are housed.

#### Biggest Challenges
Sign in/sign out & configuring backend on my own. 
Integrating an API with relatively unclear documentation.

#### Instructor Notes

#### Deliverables for next checkin:
