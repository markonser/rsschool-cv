# Konstantin Marushin

## **Contacts**
#### **tel:** +79859481258
#### **e-mail:**markonser@yandex.ru
#### **telegramm:** https://t.me/crimeanbombila

## About me
#### i want to switch my current job to frontend development job

## My skills & some knowledge
* HTML
* CSS without preprocessors
* Java Script
* Git
* React
* Figma

## Code example
```
import { CityName } from '../const/const';
import { createSlice } from '@reduxjs/toolkit';
import type { PayloadAction } from '@reduxjs/toolkit';
import { Offer } from '../types/types';
export interface State {
  selectedCity: CityName;
  offers: Offer[];
}
const initialState: State = {
  selectedCity: 'paris',
  offers: [],
};
export const reducer = createSlice({
  name: 'counter',
  initialState,
  reducers: {
    changeCity: (state: State, action: PayloadAction<CityName>) => {
      state.selectedCity = action.payload;
    },
    setOffers: (state: State, action: PayloadAction<Offer[]>) => {
      state.offers = action.payload;
    },
  },
});
export const { changeCity, setOffers } = reducer.actions;
export default reducer.reducer;
```

## Work experience
* [educational project](https://github.com/markonser/2051829-keksobooking-26)

* [real site](https://crimea.taxi)

## Courses & training
* React frontend developer

## Languages
* English - very bad