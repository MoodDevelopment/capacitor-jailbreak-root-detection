# @evehr/capacitor-jailbreak-root-detection

Jailbreak Root detection plugin for capacitor. Supports Capacior 5 and 6.
This plugin also supports Frida Detection.

a clone of @evehr/capacitor-jailbreak-root-detection repository.

## Install

```bash
npm install @evehr/capacitor-jailbreak-root-detection
npx cap sync
```

## API

<docgen-index>

* [`isJailbrokenOrRooted()`](#isjailbrokenorrooted)
* [`isFridaRunning()`](#isfridarunning)
* [`isSimulator()`](#issimulator)
* [`isDebuggedMode()`](#isdebuggedmode)
* [`exitApp()`](#exitapp)
* [Interfaces](#interfaces)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### isJailbrokenOrRooted()

```typescript
isJailbrokenOrRooted() => Promise<JailbreakRootResult>
```

**Returns:** <code>Promise&lt;<a href="#jailbreakrootresult">JailbreakRootResult</a>&gt;</code>

--------------------


### isFridaRunning()

```typescript
isFridaRunning() => Promise<JailbreakRootResult>
```

**Returns:** <code>Promise&lt;<a href="#jailbreakrootresult">JailbreakRootResult</a>&gt;</code>

--------------------


### isSimulator()

```typescript
isSimulator() => Promise<JailbreakRootResult>
```

**Returns:** <code>Promise&lt;<a href="#jailbreakrootresult">JailbreakRootResult</a>&gt;</code>

--------------------


### isDebuggedMode()

```typescript
isDebuggedMode() => Promise<JailbreakRootResult>
```

**Returns:** <code>Promise&lt;<a href="#jailbreakrootresult">JailbreakRootResult</a>&gt;</code>

--------------------


### exitApp()

```typescript
exitApp() => void
```

--------------------


### Interfaces


#### JailbreakRootResult

| Prop         | Type                 |
| ------------ | -------------------- |
| **`result`** | <code>boolean</code> |

</docgen-api>
