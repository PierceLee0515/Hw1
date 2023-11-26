# Hw1
         .font(.system(size: 45, weight: .bold))
                    .frame(width: 400, height: 100, alignment: .center)
                    .padding(.top, 0)
                    .foregroundColor(.black)
                    .offset(x: 0, y: -200)
                Image("Pierce")
                    .resizable()
                    .aspectRatio(contentMode: .fill)
                    .frame(width: 600, height: 500, alignment: .trailing)
                    .overlay(
                        
                        Text("這堂課怎麼這麼好玩")
                            .fontWeight(.heavy)
                            .lineSpacing(20)
                            .font(.system(size: 32.0))
                            .foregroundColor(.white)
                            .frame(width: 350, height: 200, alignment: .center)
                            .background(Color.green)
                            .cornerRadius(25.0)
                            .opacity(0.8)
                            .offset(x: 0, y: 55)
                            .multilineTextAlignment(.center)
                        , alignment: .bottom
                    )
                    
                    .padding(.all, 0)
                    .offset(x: 0, y: -10)
            }
                 Image(systemName: "figure.roll")
                .font(.system(size: 60, weight: .bold))
                .offset(x: 0, y: 325)
                .foregroundColor(Color(red: 45/255, green: 63/255, blue: 111/255))
        }
    }
}

```

