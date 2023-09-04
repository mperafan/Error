# Error
error con código de la librería gnark

corro "go mod tidy"
y tira el siguiente error:
machibusa@machibusapc:~/composable/prueba$ go mod tidy
go: finding module for package github.com/consensys/gnark-crypto/ecc/bls12-377
go: finding module for package github.com/consensys/gnark/std/algebra/native/sw_bls12377
go: finding module for package github.com/consensys/gnark/frontend
go: finding module for package github.com/consensys/gnark/backend/groth16/bls12-377
go: finding module for package github.com/consensys/gnark/backend/groth16
go: finding module for package github.com/consensys/gnark/std/algebra/native/fields_bls12377
go: found github.com/consensys/gnark-crypto/ecc/bls12-377 in github.com/consensys/gnark-crypto v0.11.2
go: found github.com/consensys/gnark/backend/groth16 in github.com/consensys/gnark v0.8.1
go: found github.com/consensys/gnark/frontend in github.com/consensys/gnark v0.8.1
go: finding module for package github.com/consensys/gnark/std/algebra/native/sw_bls12377
go: finding module for package github.com/consensys/gnark/backend/groth16/bls12-377
go: finding module for package github.com/consensys/gnark/std/algebra/native/fields_bls12377
prueba imports
        github.com/consensys/gnark/backend/groth16/bls12-377: module github.com/consensys/gnark@latest found (v0.8.1), but does not contain package github.com/consensys/gnark/backend/groth16/bls12-377
prueba imports
        github.com/consensys/gnark/std/algebra/native/fields_bls12377: module github.com/consensys/gnark@latest found (v0.8.1), but does not contain package github.com/consensys/gnark/std/algebra/native/fields_bls12377
prueba imports
        github.com/consensys/gnark/std/algebra/native/sw_bls12377: module github.com/consensys/gnark@latest found (v0.8.1), but does not contain package github.com/consensys/gnark/std/algebra/native/sw_bls12377
