# Fellesprosjekt
<?xml version="1.0" encoding="UTF-8"?>

<?import javafx.scene.control.*?>
<?import javafx.scene.text.*?>
<?import java.lang.*?>
<?import javafx.scene.layout.*?>
<?import javafx.scene.layout.AnchorPane?>


<AnchorPane xmlns:fx="http://javafx.com/fxml/1" xmlns="http://javafx.com/javafx/8">
   <children>
      <Pane layoutX="-100.0" layoutY="-100.0" prefHeight="300.0" prefWidth="300.0" AnchorPane.bottomAnchor="0.0" AnchorPane.leftAnchor="0.0" AnchorPane.rightAnchor="0.0" AnchorPane.topAnchor="0.0">
         <children>
            <Text layoutX="103.0" layoutY="77.0" strokeType="OUTSIDE" strokeWidth="0.0" text="Logg inn">
               <font>
                  <Font size="24.0" />
               </font>
            </Text>
            <GridPane layoutX="50.0" layoutY="126.0">
              <columnConstraints>
                <ColumnConstraints hgrow="SOMETIMES" minWidth="10.0" prefWidth="100.0" />
                <ColumnConstraints hgrow="SOMETIMES" minWidth="10.0" prefWidth="100.0" />
              </columnConstraints>
              <rowConstraints>
                <RowConstraints minHeight="10.0" prefHeight="30.0" vgrow="SOMETIMES" />
                <RowConstraints minHeight="10.0" prefHeight="30.0" vgrow="SOMETIMES" />
              </rowConstraints>
               <children>
                  <Label text="Brukernavn:" />
                  <Label text="Passord:" GridPane.rowIndex="1" />
                  <TextField promptText="Brukernavn" GridPane.columnIndex="1" />
                  <TextField promptText="Passord" GridPane.columnIndex="1" GridPane.rowIndex="1" />
               </children>
            </GridPane>
            <Button layoutX="33.0" layoutY="242.0" mnemonicParsing="false" text="Logg inn" />
            <Button layoutX="112.0" layoutY="242.0" mnemonicParsing="false" text="Ikke bruker? Meld deg inn" />
         </children>
      </Pane>
   </children>
</AnchorPane>
