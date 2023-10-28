<template>
                  <v-sheet
              id="menu"
            class="pa-3 d-flex justify-space-between mt-16"
            rounded="t-xl"
          >
          <div class="mr-16 d-inline">
          <v-chip-group
              selected-class="text-primary"
              class="d-inline"
            >
            
              <v-chip id="chip" class="ms-2" append-icon="mdi-numeric-8-circle-outline"
                v-for="tag in tags"
                :key="tag"
              >
                {{ tag }}
              </v-chip>
            </v-chip-group>
          </div>
          <div>
            <v-btn id="del" icon>
              <v-icon>mdi-delete</v-icon>
            </v-btn>
  
            <v-btn id="del" class="ms-2" icon>
              <v-icon>mdi-delete-empty</v-icon>
            </v-btn>
  
            <v-btn
              id="com"
              class="ms-2"
              icon
            >
              <v-icon>mdi-check-bold</v-icon>
            </v-btn>
          </div>
          </v-sheet>
</template>

<script setup>
const tags = [
          'All',
          'Ongoing',
          'Completed'
        ]
</script>