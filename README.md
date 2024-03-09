# principiosolid
 Principio de Responsabilidad Única (SRP)
El principio de responsabilidad única, nos dice que cada clase debe de tener una única responsabilidad y un único motivo por el que pueda ser modificada. En la clase factura existen responsabilidades que puedes ser motivo de cambio, la modificacion del iva, el porcentaje de deduccion.

Refactorización.
se extrae las responsabilidades y se crean nuevas clasea para sus correspondientes responsabilidades, estas son calcular la deduccion y calcular IVA.

Se llama desde la clase factura a las clases CalcularDeduccion y CalcularIVA para usar sus metodos, por lo que todo cambio en el iva o la deduccion afectaran sus correspondientes clases.
