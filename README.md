import { HttpStatusCode } from 'axios';

export type StatusCode = `${HttpStatusCode}`;

const code = 200 as StatusCode;

console.log(code);
