transition from 1.2 to 1.8 version -  the local workbench is not supported. so use sp workbench.
yo questions are updated, but that doesnt make much diffrence.
tslint is no longer supported, instead eslint is used. Now to make code compatible with eslint, do the following :
Comment Escape. import { escape } from '@microsoft/sp-lodash-subset';
add null assertion operators. 
