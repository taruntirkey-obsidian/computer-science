## Basic Controls

| Controls         | Description                                                                  |
| ---------------- | ---------------------------------------------------------------------------- |
| View             | Used to group other elements together. A container for other elements.       |
| Text             | Display Text.                                                                |
| Image            | Display Images either local or from the web.                                 |
| ScrollView       | List of items that the used can scroll through.                              |
| FlatList         | Render list of items. Only render items visible on the screen. No scrolling. |
| TouchableOpacity | Create a touchable component. Buttons or other interactive components.       |
| TextInput        | Takes in user input.                                                         |
| Button           | Create a button to trigger an action when pushed.                            |
| Switch           | Used to toggle value on and off.                                             |
## Styling

```
import { StyleSheet } from 'react-native'

export default function Index() {
	return (
		<View
			style={ styles.container }
		>
			<Text> Text goes here </Text>
		</View>
	)
}

const styles = StyleSheet.create({
	container: {
		flex: 1,
		justifyContent: 'center',
		alignItems: 'center'
	}
})
```

## Layout

**\_layout.tsx**

**Stack** for multiple screens.
**Slot** for single screen apps.