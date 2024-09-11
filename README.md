# I2C class for M5Stack Basic & Gray

## I2C class

## Methods

### I2C.new() -> I2C

Creates I2C object.

---

### I2C#read(addr, len, *outdata) -> String

Read data from I2C.

#### Parameters

- addr  
Slave address of I2C device.

- len  
Data length for read.

- *outdata

Output data before read.

#### Return

Array of read data.

---

### I2C#write(addr, len, *outdata) -> bool

#### Parameters

- addr  
Slave address of I2C device.

- len  
Data length for read.

- *outdata

Output data.

#### Return

Result of write. (true: Success, false: Failure)

## License

under the MIT License.
