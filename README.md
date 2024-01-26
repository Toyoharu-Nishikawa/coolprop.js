# coolprop.js


### samplle code

```
import CoolProp from "./node_modules/coolprop.js"

const main = async () => {
  const cp = await CoolProp()
  const density = cp.PropsSI('D', 'T', 298.15, 'P', 100e5, 'CO2')
  console.log(density)
}
main()

```
