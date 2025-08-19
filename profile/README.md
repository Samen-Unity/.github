# Samen - Real-time Scene Collaboration in Unity
**Samen** lets multiple level designers work together in the *same* scene at the *same* time.  
Think Google Docs, but for Unity. Changes are live-synced between all users in real time.


# Releases 
### [🌐 Server Releases](https://github.com/Samen-Unity/samen-host/releases)
### [🧑‍💻 Client Releases](https://github.com/Samen-Unity/samen-sample/releases)

# 🕑Feature Timeline:
- ✅ Multi-user session system  
- ✅ Custom packet protocol  
- ✅ Real-time sync of object position, rotation, and scale  
- ✅ Robust server-side history system  
- ✅ Object duplication & deletion syncing  
- ✅ In-session chat & command system  
- ✅ Prefab loading  
- ✅ Ping tool  
- ✅ Auto-reconnect  
- ✅ User management & permissions  
- ✅ External plugin support  
- 🛠️ Camera avatar support for other users  
- 🛠️ Selection outline sync  
- 🛠️ Tilemap support
- 😴 Syncing components in session
- 😴 Creating new objects in session
- 🛠️ ...and more to come

## 📣 Are You Using Samen?
If your team is using Samen, I’d love to hear from you!  
Let’s connect and scheme some epic plans for future updates.

## 👥 Current Contributors
@TygoDeVries (Maintainer, Core Contributor)  
@Pruyque (Contributor)

## 😴 Known issues
Creating new objects and adding components to objects during a session is a difficult challange, and is still being worked on. 
For now, create the needed objects beforehand as prefabs. You can add prefabs from your files during a live session.

## 🔄 Version Compatibility

| Client Version(s)       | Server Version(s)   | Protocol Version |
|------------------------|--------------------|------------------|
| v0.1.0                 | v0.1.0             | 1                |
| v0.2.0                 | v0.2.0             | 2                |
| v0.3.0, v0.3.2, v0.3.3  | v0.3.0             | 3                |

> **Note:**  
> - Compatibility depends on matching protocol versions.  
> - Minor patch versions (sub-versions) are backward compatible within the same protocol.  
> - Always update client and server to the latest compatible protocol version for best stability.

